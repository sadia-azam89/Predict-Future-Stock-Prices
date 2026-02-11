# 📈 Predict Future Stock Prices

A machine learning project that predicts the **next day’s closing price** of a stock using historical market data from Yahoo Finance.
## 🚀 Overview
This notebook:

* Downloads stock data using `yfinance`
* Uses **Open, High, Low, Volume** as features
* Predicts the **next day’s Close price**
* Trains and compares:
  * Linear Regression
  * Random Forest Regressor
* Plots **Actual vs Predicted** prices

## 📊 Data Source

* Yahoo Finance (via `yfinance`)
* Example stock: `AAPL` (Apple)
  *(You can change to TSLA or any ticker symbol.)*

## 🛠️ Tech Stack

* Python
* Pandas & NumPy
* Matplotlib
* Scikit-learn
* Google Colab / Jupyter Notebook

## 📈 Output
* Model evaluation (MAE, RMSE, R²)
* Actual vs Predicted price visualization
* Next-day closing price prediction
## ▶️ How to Run
```bash
pip install yfinance pandas numpy matplotlib scikit-learn
```
Open the notebook and run all cells.
---
