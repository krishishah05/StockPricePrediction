# StockPricePrediction
Overview

This project leverages Long Short-Term Memory (LSTM) neural networks to forecast stock prices. It utilizes historical stock price data sourced from Yahoo Finance and integrates technical indicators such as the Relative Strength Index (RSI) to train the model and generate predictions.

Features

- Data Acquisition: Fetches historical stock price data from Yahoo Finance using the yfinance library.
- Data Preprocessing: Prepares the data by incorporating technical indicators like RSI.
- Model Architecture: Implements LSTM neural networks, well-suited for sequential data prediction tasks.
- Evaluation: Assesses model performance with metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
- Visualization: Provides visual comparison of actual vs. predicted stock prices using matplotlib.

Performance Metrics

- Mean Absolute Error (MAE): Achieved an MAE of $3.22, indicating the average absolute difference between predicted and actual stock prices.
- Root Mean Squared Error (RMSE): Achieved an RMSE of $3.85, a measure of the model's prediction accuracy over a 10-year dataset.

Summary
This project demonstrates the application of LSTM neural networks in forecasting stock prices, utilizing both historical data and technical indicators. By leveraging sequential data capabilities of LSTMs and incorporating relevant financial indicators, the model achieves competitive accuracy in predicting future stock prices.
