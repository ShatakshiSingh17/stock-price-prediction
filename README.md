
# 📈 Stock Price Prediction & Risk Analysis | Multi-Company | ML-Driven Forecasting

---

## Executive Summary

This project focuses on predictive modeling and risk analysis of stock price trends for six leading companies — AMD, ASUS, Intel, NVIDIA, Microsoft, and Amazon — using historical data ranging from 1980 to 2023.

Utilizing machine learning regressors (Random Forest, HistGradientBoosting), statistical methods (ARIMA), and financial technical indicators, this project delivers a comprehensive Python-based analytics solution. The model forecasts future prices, evaluates volatility and performance, and provides insights into daily return trends.

---

## Table of Contents

* [Executive Summary](#-executive-summary)
* [Business Objectives](#-business-objectives)
* [Key Features](#-key-features)
* [Technologies Used](#-technologies-used)
* [Project Structure](#-project-structure)
* [Modeling Approach](#-modeling-approach)
* [Evaluation Metrics](#-evaluation-metrics)
* [Forecast Output](#-forecast-output)
* [Learning Outcomes](#-learning-outcomes)
* [How to Run](#-how-to-run)
* [Dataset Source](#-dataset-source)

---

## Business Objectives

* Predict stock prices for AMD, ASUS, Intel, NVIDIA, Amazon, and Microsoft.
* Evaluate trends and volatility using technical indicators and daily return analysis.
* Compare model performance across companies and algorithms.
* Provide actionable insights into investment risk and performance.

---

## Key Features

* Multi-company support: AMD, ASUS, Intel, NVIDIA, Microsoft, Amazon
* Time-series forecasting using:

  * Random Forest Regressor
  * Histogram-based Gradient Boosting Regressor
  * ARIMA with exogenous features
* Technical indicator computation:

  * SMA, EMA, RSI, MACD, Bollinger Bands, Stochastic Oscillator
* Daily return and VaR (Value at Risk) analysis
* Sentiment analysis integration with stock news (VADER-based)
* Visualization of actual vs predicted closing prices

---

## Technologies Used

* Python
* pandas, numpy
* scikit-learn, statsmodels
* matplotlib, seaborn
* Technical indicators via rolling/ewm logic
* (Optional modules used earlier: `talib`, `vaderSentiment` — removed for portability)

---

## Project Structure

```
stock-price-prediction/
├── datasets/
│   ├── AMD (1980 -11.07.2023).csv
│   ├── ASUS (2000 - 11.07.2023).csv
│   ├── Intel (1980 - 11.07.2023).csv
│   ├── NVIDIA (1999 -11.07.2023).csv
│   ├── MSFT.csv
│   └── AMZN.csv
├── stock_prediction_main.py
└── README.md
```

---

## Modeling Approach

* **Preprocessing:** Date formatting, missing value handling, computation of rolling statistics
* **Feature Engineering:** Technical indicators calculated using basic pandas operations
* **Train/Test Split:** 80/20 split with time-based ordering
* **Models Applied:**

  * Random Forest Regressor
  * Histogram-based Gradient Boosting Regressor
  * ARIMA with exogenous features

---

## Evaluation Metrics

* **RMSE (Root Mean Squared Error)** used to evaluate model performance.
* **Visual comparison** of predicted vs actual closing prices.

---

## Forecast Output

Each company includes:

* Technical indicator visualizations
* Forecast plots for the next 30–100 days
* RMSE results
* Model comparison charts

---

## Learning Outcomes

* Built end-to-end ML pipelines for financial time-series
* Applied ensemble methods and statistical forecasting models
* Engineered financial indicators without external libraries
* Developed modular, readable Python scripts
* Enhanced understanding of stock price dynamics


## Dataset Source
This project uses daily historical stock price data for six major technology companies: Amazon (AMZN), AMD, NVIDIA, ASUS, Intel, and MSI, with records dating back to 1997. 

 Sources:
*Amazon Stock Data (Kaggle)
*NVIDIA, AMD, Intel, ASUS, MSI Share Prices (Kaggle)

