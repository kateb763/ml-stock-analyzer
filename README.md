# ml-stock-analyzer

A simple machine learning project to predict stock movements using historical data and technical indicators.
This project uses historical stock price data from Yahoo Finance, applies technical analysis features like moving averages and RSI, and predicts price movement using XGBoost.

## Features
- Yahoo Finance integration via `yfinance`
- Feature engineering (Moving Averages, RSI)
- Predictive modeling with `XGBoost`
- Optional dashboard with `Streamlit`
- Backtesting support to evaluate strategy performance

## Tech Stack
- Python
- Pandas, NumPy
- yfinance, scikit-learn, XGBoost
- Matplotlib 

## Installation
```bash
git clone https://github.com/katebroulik/stock-predictor.git
cd stock-predictor
pip install -r requirements.txt
