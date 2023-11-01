# Stock Price Prediction

This project focuses on predicting stock prices using a linear regression model. It takes historical stock data and provides predictions for future stock prices.

## Table of Contents

- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Dataset](#dataset)

## Project Overview

The Stock Price Prediction project employs a linear regression model to predict future stock prices. It processes historical stock data and uses features such as lag prices, trading volume, and rolling means to make predictions.

- Features: Close price lag, Volume, Rolling Mean of Close Prices

The project is designed as a Python script for data preprocessing, model training, and evaluation.

Read the documentation file for further clarifications.

## Getting Started

To start using this code, follow these steps:
- To use it in local machine convert to `.py ` file and use it.
- Clone the repository to your local machine:
  `git clone https://github.com/yuvan-s-96/stock-price-prediction.git`
- Install the required libraries:
`pip install pandas scikit-learn matplotlib`
- Run the Python Script:
`python stock_price_prediction.py`
- View the model's performance metrics, including Mean Absolute Error (MAE), R-squared (R2) score, and accuracy.
- Incase you are using Google colab or jupyter notebook directly download the `.ipynb ` file and run it.

## Usage
To use the Stock Price Prediction code:

- Place your historical stock data in a CSV file named 'MSFT.csv' in the same directory. Ensure that the CSV file contains at least the following columns: 'Date', 'Close', and 'Volume'.

- Run the Python script to execute data preprocessing, model training, and evaluation.

## Dataset
- The dataset appears to be historical stock price and volume data for Microsoft (MSFT).
- Columns in the dataset include 'Date', 'Close' (closing stock price), and 'Volume' (trading volume).
- The data appears to be time-series data as it's indexed by date.
- Get the dataset from link:
`https://www.kaggle.com/datasets/prasoonkottarathil/microsoft-lifetime-stocks-dataset`

