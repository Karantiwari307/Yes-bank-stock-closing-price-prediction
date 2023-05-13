Yes-bank-stock-closing-price-prediction

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.
ABSTRACT:
Accurate prediction of stock market returns is a very challenging task due to the volatile and non-linear nature of the financial stock markets. With the introduction of machine learning, time series forecasting, and increased computational capabilities, programmed methods of prediction have proved to be more efficient in predicting stock prices. In this work, regression and time series forecasting techniques have been utilized for predicting the next day closing price for one company belonging to the Finance sector of operation. The financial data: Open, High, Low, and Close prices of stock are used for creating new variables which are used as inputs to the model. The models are evaluated using standard strategic indicators: RMSE and MAPE. The low values of these two indicators show that the models are efficient in predicting stock closing prices.
The Yes Bank Data is first extracted and then categorized to identify, analyze behavior data and patterns. Using this dataset in our Supervised ML-Regression project we found some relevant analysis which would help to predict the monthly stock’s closing price of Yes Bank to perform better.
Data set - data_YesBank_StockPrices - contains observations regarding open, close, high and low prices of the yes bank stock from July 2005 – November 2020.
Rows: 185
Column: 5
Date: It denotes the month and year for a particular price.
Open: Open means the price at which a stock started trading that month.
High: refers to the maximum price that month.
Low: refers to the minimum price that month.
Close: refers to the final trading price for that month, which we have to predict using regression technique.
The objective of this project is to predict the stock’s closing price of the month. Discussion of Yes Bank Dataset will involve various steps such as:
Loading the data into data frame
Cleaning the data
Extracting statistics from the dataset
Exploratory analysis and visualizations
Train Test Split
Linear Regression
Lasso Regression
Ridge Regression
XGBoost Regression
