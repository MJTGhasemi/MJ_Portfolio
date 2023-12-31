# Portfolio
---

## Stock Price EDA and Analysis (Time Series)

An Exploratory Data Analysis (EDA) and Time Series Analysis have been conducted on stock prices. The data is fetched for four companies: `Apple`, `Google`, `Microsoft`, and `Amazon` from **2018-01-01** to **2023-07-31** using **Yahoo Finance**. By the end of this notebook, we hope to have extracted meaningful insights from our data and built a reliable time series model that can predict future stock prices. 

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/MJTGhasemi/ML_Projects/tree/main/Stocks%20Analysis)

- The stock data is visualized using line plots and bar plots. These visualizations include volume over time for each company, daily price change, monthly and yearly average closing prices for Apple, pairplots, heatmaps of closing prices and daily returns for all companies, and more.

- The closing prices are transformed to their logarithmic form to stabilize the variance. The data is split into training and testing sets in a chronological manner.

- The Augmented Dickey-Fuller (ADF) test is performed on the training data to check for stationarity. The rolling mean and standard deviation are also plotted.

- Autocorrelation and partial autocorrelation plots are generated for the differences in the closing prices.

- An ARIMA model fits the training data using the auto_arima function, which automatically determines the model's best parameters (p, d, q). 

- The trained model is used to forecast the closing prices for the test set. The forecasts are plotted alongside the actual values. The residuals of the model are also plotted, and their statistics are displayed. Root Mean Square Error (RMSE) and Mean Absolute Percentage Error (MAPE) are calculated to evaluate the performance of the model.

<center><img src="Images/Stocks.png"/></center>
