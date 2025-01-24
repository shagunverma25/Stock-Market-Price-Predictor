# Stock-Market-Price-Predictor
The Stock Market Price Prediction project is a ML based web application that uses historical stock data to predict future stock prices. The app utilizes a LSTM model, a type of RNN, to make accurate predictions on stock price trends. Users can input a stock symbol, view the historical data, and compare the actual prices with predicted values over time.

This project provides an easy-to-use interface built with Streamlit and integrates data from yFinance for real-time stock data retrieval.

Features:
Real-time Stock Data: Fetch stock data from Yahoo Finance using yFinance.
Stock Price Prediction: Predict future stock prices using an LSTM model trained on historical data.
Interactive Visualizations: Visualize stock prices, moving averages (MA50, MA100, MA200), and predicted vs. actual stock prices using Matplotlib.
User Input: Users can input any stock symbol (e.g., 'GOOG', 'AAPL') and see predictions and stock data.

Technologies Used:
Python
Keras (for building and training the LSTM model)
Streamlit (for creating the interactive web app)
yFinance (for fetching stock data)
Scikit-learn (for data scaling)
Matplotlib (for plotting graphs and visualizations)
