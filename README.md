# 📈 Stock Price Prediction using Machine Learning

This project implements a **machine learning–based time-series regression model** to predict stock closing prices using historical OHLCV data.  
It demonstrates an end-to-end ML workflow including preprocessing, feature engineering, model training, and quantitative evaluation.

---

## 🎯 Problem

Predict the **future Close price** of a stock using past market data while preserving temporal dependencies.

---

## 🧠 ML Approach

- **Type:** Time-Series Regression  
- **Features:** Open, High, Low, Close, Adj Close, Volume  
- **Target:** Close Price  
- **Validation:** Chronological train–test split  

---

## 🧪 Model

- Regression-based ML baseline  
- Extendable to LSTM / GRU / CNN-LSTM models

---

## 📊 Evaluation Metrics

- MAE  
- RMSE  
- R² Score  

### Results Summary

| Metric | Value |
|------|------|
| MAE | 14.13 |
| RMSE | 3.75 |
| R² | 0.96 |

---

## 🛠️ Tech Stack

Python · pandas · NumPy · scikit-learn · matplotlib · yfinance · Jupyter

---

