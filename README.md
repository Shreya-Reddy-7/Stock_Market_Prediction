#Stock_Market_Prediction

Predicting Stock Market Trends Using Historical Data with Deep Learning:

  This project aims to forecast stock market trends using historical stock price data and a deep learning model, particularly Long Short-Term Memory (LSTM) networks. By capturing temporal dependencies in time-series data, the model helps predict future stock movements with strong accuracy metrics.

Problem Statement:

  The stock market is inherently volatile, influenced by numerous unpredictable factors. Traditional statistical models often fail to capture complex non-linear relationships in stock prices. This project addresses this gap by using deep learning models like LSTM to analyze and predict future stock trends more reliably.

Objectives:

- Analyze and visualize historical stock data (Open, Close, High, Low, Volume).
- Preprocess and normalize time-series data.
- Engineer technical indicators (e.g., Moving Averages, RSI).
- Design and train an LSTM-based model.
- Evaluate model performance using metrics like MAE, RMSE, and R².
- Forecast future stock prices and trends with visual outputs.

Technologies Used:

- Language: Python 3.x
- Libraries: - TensorFlow / Keras
             - Pandas, NumPy
             - Scikit-learn
             - Matplotlib, Seaborn
             - yfinance
- Environment: Google Colab / VS Code
- Data Source: Yahoo Finance API

Dataset

- Source: [Yahoo Finance](https://finance.yahoo.com/) via `yfinance` API
- Content: Daily stock data including Open, High, Low, Close, and Volume
- Preprocessing:
  - Handling missing values
  - Min-Max Normalization
  - Feature generation: 100-day and 200-day Moving Averages, RSI, lag features

