# LSTM Neural Network to perform Time Series Analysis to predict the next day Stock Price

Author: Steven Zhang, Georgia Institute of Technology


# Project Overview
We utilize LSTM(Long-Short-Term-Memory) or Recurrent Neural Network in our implementation to predict Stock Prices as we have a time series problem by predicting the stock price of the following day given data from previous days. Using LSTM comes in handy as RNN's are able to retain information regarding the performance of the stock from the past number of days hence the term "memory". Using LSTM's memory attribute, we can solve this Time Series Problem.

The Stock_Price_Prediction.ipynb notebook contains the code and outputs for using RNN's to model stock prices. This implementation was inspired by a Udemy Tutorial. This file implements TensorFlow training from your local computer's CUDA GPU's. We try to model the next day stock price based on the previous fifty days stock data. More specifically, given what the stock price of AAPL during the last fifty days, this model generates a prediction for the next day or the fifty-first day. We can generate as many predictions as we want just from the last fifty days of known stock prices.

The black-scholes.ipynb notebook contains the code and outputs for a simple implementation of the Mathematical Model Black Scholes. More implementation testing will be needed to use the Black Scholes Model on stock prediction. (Work in progress)

# Project Outcome
Below we can see some sample predictions of what our model would have predicted for AAPL's stock price for a year based on the past 50 days of stock price. 

![LSTM Model Prediction Graph](https://github.com/stevenzhang070302/LSTM-Model-Predicting-Stocks/blob/main/LSTM_Pred_1.png)

![LSTM Model Prediction Graph Zoomed-in](https://github.com/stevenzhang070302/LSTM-Model-Predicting-Stocks/blob/main/LSTM_Pred_2.png)
