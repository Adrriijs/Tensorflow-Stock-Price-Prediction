# 🚀 LSTM-Based Stock Price Prediction with TensorFlow

This project focuses on predicting stock prices for **Vanguard S&P 500 ETF (VFV.TO)** using **Long Short-Term Memory (LSTM) networks** powered by **TensorFlow**. By leveraging historical stock market data from **Yahoo Finance**, the model identifies trends and forecasts the **next day's closing price**.

## 📊 Data Source: Yahoo Finance
The dataset includes:
- **Closing Prices**: Adjusted closing prices for VFV.TO over multiple years.
- **Time Series Features**: The model uses **the past 60 days of stock prices** to generate future predictions.

## 🔥 Key Features
✔ Fetches and Preprocesses Stock Data from **Yahoo Finance**
✔ Implements an **LSTM Neural Network** for Time-Series Forecasting
✔ Trains and Validates the Model Using **TensorFlow & Keras**
✔ Evaluates Performance Using **Mean Squared Error (MSE)**
✔ Generates **Visual Comparisons** of Predicted vs. Actual Stock Prices
✔ Provides a **Next-Day Stock Price Prediction**

## Setup
To set up the project, install the yfinane python library


## 📈 Model Performance
- The model is trained using **LSTM layers** to capture sequential patterns in stock price movement.
- **MSE (Mean Squared Error)** is used to measure the accuracy of the predictions.
- **Visual Graphs** help in assessing how well the model tracks real market trends.

## 🔮 Future Enhancements
- Incorporate **technical indicators** (e.g., Moving Averages, RSI) to improve accuracy.
- Optimize **hyperparameters** for better model generalization.
- Experiment with **alternative deep learning models** (e.g., GRU, Transformer networks).
