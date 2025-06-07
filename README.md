# Stock Price Predictor

## Project Overview
This project implements a simple machine learning model to predict the next day's closing price of Apple Inc. (AAPL) stock using historical closing prices.  
The model is built using **Linear Regression** and trained on stock data from 2018 to 2024.

---

## Dataset
- Stock data is fetched dynamically from Yahoo Finance using the `yfinance` Python library.
- Data range: January 1, 2018 to December 31, 2024.
- Only the closing prices are used as features.
- The target variable is the closing price of the next trading day.

---

## Objective
- Predict the next day’s closing stock price based on today’s closing price.
- Evaluate model performance using Mean Squared Error (MSE) and R-squared score.
- Visualize how closely the predicted prices align with actual prices.

---

## Technologies & Libraries Used
- Python 3.x
- [yfinance](https://pypi.org/project/yfinance/) - To download stock market data.
- pandas, numpy - For data manipulation.
- matplotlib - For visualization.
- scikit-learn - For building and evaluating the regression model.

---

## Installation

To run the project, first install the required libraries:

```bash
pip install yfinance pandas numpy matplotlib scikit-learn
