# Stock-Price-Prediction-for-CSCO-and-AMZN-Using-LSTM

This project aims to predict the daily closing stock prices of two major technology companies, Cisco Systems (CSCO) and Amazon.com (AMZN), using the Long Short-Term Memory (LSTM) model. Historical stock price data is sourced from Yahoo Finance via the yfinance Python package, with data up to April 1, 2020.

LSTM is chosen due to its strength in identifying patterns in time series data, which is crucial for stock price forecasting.


### Dataset
The dataset includes key stock information such as:
- Open Price (Open)
- High Price (High)
- Low Price (Low)
- Close Price (Close)
- Adjusted Close Price (Adj Close)
- Daily Trading Volume (Volume)
This project focuses on the Date and Close columns to predict future closing stock prices.
