# Stock-Price-Prediction-for-CSCO-and-AMZN-Using-LSTM

This project aims to predict the daily closing stock prices of two major technology companies, Cisco Systems (CSCO) and Amazon.com (AMZN), using the Long Short-Term Memory (LSTM) model. Historical stock price data is sourced from Yahoo Finance via the yfinance Python package, with data up to April 1, 2020. LSTM was selected for this task because it excels at identifying patterns in time series data, which is essential for accurately forecasting stock prices.

## Dataset
The dataset includes important stock information such as:

Open Price: The price at which the stock opened for trading.

High Price: The highest price reached during the trading day.

Low Price: The lowest price reached during the trading day.

Close Price: The price at which the stock closed for trading.

Adjusted Close Price: The closing price adjusted for dividends and stock splits.

Daily Trading Volume: The total number of shares traded during the day.

For this project, I focused on the Date and Close columns to predict future closing stock prices.

## Approach
I developed two LSTM models: a baseline model and a modified version. The baseline model provided a foundation for understanding the data, while the modified model included enhancements to improve performance. I evaluated the models based on key metrics such as RMSE (Root Mean Square Error), MAE (Mean Absolute Error), and MAPE (Mean Absolute Percentage Error) to see which one performed better.

## Results
The modified LSTM model outperformed the baseline model, showing lower error rates for both CSCO and AMZN. However, I encountered challenges with AMZN's stock prices, particularly due to their high volatility after 2010, which led to some overfitting in the model. Despite these challenges, this project demonstrated the potential of LSTM models in predicting stock prices and provided valuable insights into the forecasting process.

