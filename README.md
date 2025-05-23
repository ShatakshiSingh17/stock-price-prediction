# Stock Price Prediction and Analysis Using Machine Learning

This project applies machine learning techniques to predict stock prices for major tech companies including AMD, ASUS, Intel, NVIDIA, Microsoft, and Amazon. It uses historical price data and technical indicators to train regression models and forecast future trends.

## 🔍 Key Features

- Exploratory Data Analysis (EDA) on stock data from 1980–2023
- Computation of technical indicators (SMA, EMA, RSI, MACD, Bollinger Bands, etc.)
- Stock price forecasting using:
  - Random Forest Regressor
  - Histogram-based Gradient Boosting Regressor
- Model performance evaluation using RMSE
- Visualization of actual vs predicted prices

## 📁 Project Structure

stock-price-prediction/
├── datasets/
│ ├── AMD (1980 -11.07.2023).csv
│ ├── ASUS (2000 - 11.07.2023).csv
│ ├── Intel (1980 - 11.07.2023).csv
│ ├── NVIDIA (1999 -11.07.2023).csv
│ ├── MSFT.csv
│ └── AMZN.csv
├── stock_prediction_main.py
└── README.md


## 🛠 Technologies Used

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn

## 📊 Output

- Stock price plots with technical indicators
- Predicted vs actual closing prices
- RMSE evaluation metrics

