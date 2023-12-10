# DE Project - Financial Futurists

This repository contains notebooks and data for the Data Engineering project. The project focuses on the analysis and prediction of Indian and US stocks.

The repository is organized into the following directories:

## [Indian_stocks_analysis](./Indian_stocks_analysis)

This directory contains the analysis of Indian stocks.

- [`stock_analysis.ipynb`](./Indian_stocks_analysis/stock_analysis.ipynb): This Jupyter notebook contains the analysis of Indian stocks based on financial and stock price data.

## [Indian_stocks_prediction](./Indian_stocks_prediction)

This directory contains the prediction models for Indian stocks.

- [`clustering.ipynb`](./Indian_stocks_prediction/clustering.ipynb): This Jupyter notebook contains the clustering of Indian stocks.
- [`StockPricePrediction.ipynb`](./Indian_stocks_prediction/StockPricePrediction.ipynb): This Jupyter notebook contains the stock price prediction models like Linear Regression & Random Forest.
- [`stock_prediction_avg_based_xgboost.ipynb`](./Indian_stocks_prediction/stock_prediction_avg_based_xgboost.ipynb): This Jupyter notebook contains the XGBoost model for stock prediction based on average values.

## [Ind_vs_US_stocks_analysis](./Ind_vs_US_stocks_analysis)

This directory contains the comparative analysis of Indian and US stocks.

- [`India_EDA.ipynb`](./Ind_vs_US_stocks_analysis/India_EDA.ipynb): This Jupyter notebook contains the exploratory data analysis (EDA) of Indian stocks.
- [`US_EDA.ipynb`](./Ind_vs_US_stocks_analysis/US_EDA.ipynb): This Jupyter notebook contains the exploratory data analysis (EDA) of US stocks.

**Dataset**

This project uses the following datasets:

**Hourly data of BSE India stocks:** This dataset is sourced from kite.zerodha.com and contains the volume, open/high/low/close price of stock data.

**Industry / sector data for BSE India stocks:** This data is scraped from the NSE website and contains sector / industry and other meta data of the company.

**Financial data of last 3-5 quarters of BSE India stocks:** This data is sourced from the Yahoo Finance API.
