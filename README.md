# Stock-Price-Prediction
SOLARINDS Stock Price Prediction using LSTM

This project implements a Long Short-Term Memory (LSTM) neural network to predict stock prices of SOLARINDS based on historical data. The model is trained on a time-series dataset, utilizing MinMaxScaler for normalization and a three-layer stacked LSTM architecture to capture long-term dependencies.

Model Overview:
Data Preprocessing: Uses MinMaxScaler for feature scaling and constructs input sequences with a time step of 60 days.

Architecture:
Three LSTM layers (100 units each) with Dropout (0.2) to prevent overfitting.
A Dense layer for final prediction.
Compiled with Adam optimizer and Mean Squared Error (MSE) loss function.

Training: Runs for 20 epochs with a batch size of 32.

Prediction: The model predicts future stock prices, and results are visualized using Matplotlib.

Visualization:
The plot compares actual vs. predicted stock prices, where:
Red line: Actual stock price
Green line: Predicted stock price
