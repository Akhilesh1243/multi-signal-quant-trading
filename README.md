# **Multi-Signal Quant Trading Project**

📖 **Overview**

This project builds a quantitative trading framework using multiple signals extracted from stock data, news sentiment, and technical indicators.
It combines basic feature engineering and a deep learning model (LSTM) to predict future volatility.

🎯 **Project Aim**

  Perform feature engineering on stock market data (returns, moving averages, volatility).
  
  Conduct sentiment analysis on news headlines using FinBERT.
  
  Merge engineered features + sentiment into a single dataset.
  
  Build an LSTM neural network to predict future volatility of a stock.

🛠️ **Methods / Models Used**: 

  1. Feature Engineering
     
    Moving Averages (MA20)
    Log Returns
    Rolling Volatility (20-day window)

  2. Sentiment Analysis
     
    Using FinBERT model to classify headlines into Positive, Negative, or Neutral.
    Mapping sentiments into numerical scores (+1, 0, -1).

  3. LSTM Model

    Sequence learning using LSTM to predict 20-day volatility.
    Trained using PyTorch and evaluated using MSE Loss.


**🖥️ Technologies Used**

    Python
    
    Pandas
    
    NumPy
    
    Scikit-learn
    
    PyTorch
    
    Matplotlib

📈 **Results**

    Successfully trained an LSTM model to predict volatility.
    
    Model shows good learning but slight flattening in predictions due to small dataset.
    
    Future improvements include dataset expansion and advanced model architectures.
