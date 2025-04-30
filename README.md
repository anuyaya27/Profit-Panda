# Profit Panda – Smart Stock Predictor for Food & Hospitality

**Profit Panda** is a machine-learning-powered trading bot designed to make informed stock predictions, particularly for companies in the **food and hospitality industry**. Inspired by the branding of fast-food chains like Panda Express, this Python-based tool collects real-time market data, extracts meaningful features, and makes future price movement predictions to help users make smarter investment decisions.

---

## Features

- **Real-Time Data Collection** from Yahoo Finance and Binance
- **Custom ML Classifier** trained on historical price movements
- **Technical Indicator Generator** (moving averages, RSI, etc.)
- **Sector-Specific Focus** on food & hospitality industry stocks
- **Modular Codebase** with clean separation of data collection, feature engineering, model training, and prediction

---

## Tech Stack

- **Language**: Python 3.x  
- **Libraries**: 
  - `pandas`, `numpy` – data wrangling  
  - `scikit-learn`, `xgboost` – machine learning  
  - `yfinance`, `ccxt` – financial data collection  
  - `matplotlib`, `seaborn` – optional visualization  

---

## How It Works

1. **Data Collection**  
   Modules like `collector_yfinance.py` and `collector_binance.py` fetch historical and current price data.

2. **Feature Engineering**  
   `analyzer.py` generates features such as price momentum, volatility, and technical indicators.

3. **Model Training & Prediction**  
   `classifiers.py` contains the logic to train an ML model (e.g., XGBoost) and make buy/sell predictions.

4. **Execution**  
   Run `App.py` to initialize and execute the pipeline end-to-end.

---
