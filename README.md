# Stock-Market-Prediction
Built an LSTM-based model to forecast stock prices using historical data. Handled preprocessing, hyperparameter tuning, and  deployed via Streamlit app for real-time predictions. 


This project demonstrates how to build and train an LSTM (Long Short-Term Memory) deep learning model to predict the next-day closing price of a stock using historical market data.

The model uses:

Yahoo Finance API (yfinance) for fetching historical data

MinMax scaling + lookback window for sequence preparation

Two-layer LSTM neural network

Matplotlib for visualizing actual vs predicted performance

The script allows the user to input any stock ticker and automatically trains a new model on the selected stock.

-Features

Fetches historical stock data (Close price only)

Preprocesses data using scaling & lookback sequences

Builds and trains a deep learning LSTM model

Predicts the next-day closing price

Visualizes:

Actual prices

Model-predicted prices

Fully standalone Python script
