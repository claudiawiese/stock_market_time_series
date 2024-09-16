## Google Stock Time Series Analysis

### Project Description 
This project aims at analyzing and forecasting any patterns of weekly google stock data collected between 2015 and 2020. 
After the pre-processing the data, it will be modelized with the classical time series models ARIMA and SARIMA as well as with a more advanced deep learning LSTM model. 

### Results
ARIMA and SARIMA models did a very bad job in modelling the goole stock time series. The deep learning LSTM model did a much better job modelling the time series. 

### Data Source
Historical stock market data was obtained from Yahoo Finance

### Running the project
If you want to compute yourself our results you have to clone the github repository to your local machine and run the corresponding jupyter notebooks in the folder modelling.

### Project Structure 
project_root/
├── db/
    ├── google_stock_data.csv
    ├── log_stock_data.csv
│   └── preprocessed_stock_data.csv
├── modelling/
│   ├── ARIMA_modelling.ipynb
│   ├── LSTM_modelling.ipynb
│   └── SARIMA_modelling.ipynb
└── preprocessing/
    └── preprocessing.ipynb
   