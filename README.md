# Time-series-ARIMA-ARMA-

What is a time series?

According to the wikipedia, A time series is a series of data points indexed (or listed or graphed) in time order. Most commonly, a time series is a sequence taken at successive equally spaced points in time. Thus it is a sequence of discrete-time data. For example, stock prices over a fixed period of time, hotel bookings, ecommerce sales, waether cycle reports etc.

Time series analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data. Time series forecasting is the use of a model to predict future values based on previously observed values.

Let's discuss a few definitions related to time series first.

Definitions

Level: Level is the average of the values of the series.

Trend: Trend shows a pattern in the data. For example, whether the stock prices are increasing with time(uptrend) or are they decreasing with time(downtrend) or time doesn't have that much effect on the prices(Horizontal trend)

Seasonality: When the data shows a repetative pattern for over an year, it can be termed as seasonal pattern. For example, the sale of airconditioners will increase every year during summer and the sale will decrease during winter.

Cyclic Patterns: These are the repetative patterns shown over a longer period of time(more than one year). For example, after every five year the share market has some fluctuations due to the general elections.

Noise: The variations which do not show any pattern.


Let's now take an example to see what was done before the advent of Time Series Analysis.

Let's say that we have a problem at hand where we have been asked to predict the sales of skiing products for a sports manufacturer. You can do the predictions using the following methods:

Old Methods

Using Average: You might give the prediction as the average of all the prevous values.

Using Moving Average: This is the average of the previous values over a fixed period. For example you might predict the sales in November based on the average of past 3 months. The past three months will be August, September and October. If you are predicting the sales for December, the past three months will be September, October and November. Although the number of months considered are same but the window moved from one set of months to another. Hence the name Moving Average.

Using the Naive Method: The Naive method says that the prediction will be same as the last figure. For example, the prediction for November will be the sales for October.

Using the Seasonal Naive Method: Seasonal naive method is similar to naive method. Here, the new prediction is equal to the sales for the previous season.
