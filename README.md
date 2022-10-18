
# Stock Price Predication - using Time Teries 

## Time series data
Time series data is a sequence of data points in chronological order that is used by businesses to analyze past data and make future predictions. These data points are a set of observations at specified times and equal intervals, typically with a datetime index and corresponding value. Common examples of time series data in our day-to-day lives include:

1-Measuring weather temperatures

2-Measuring the number of taxi rides per month

3-Predicting a company’s stock prices for the next day

# Components of Time Series¶
*Time series data consist of four components:


*Trend Component: This is a variation that moves up or down in a reasonably predictable pattern over a long period.

*Seasonality Component: is the variation that is regular and periodic and repeats itself over a specific period such as a day, week, month, season, etc.,

*Cyclical Component: is the variation that corresponds with business or economic 'boom-bust' cycles or follows their own peculiar cycles, and

*Random Component: is the variation that is erratic or residual and does not fall under any of the above three classifications.

# Conclusion
Python’s pandas library is a powerful, comprehensive library with a wide variety of inbuilt functions for analyzing time series data. In this article, we saw how pandas can be used for wrangling and visualizing time series data.

We also performed tasks like time sampling, time shifting and rolling with stock data. These are usually the first steps in analyzing any time series data. Going forward, we could use this data to perform a basic financial analysis by calculating the daily percentage change in stocks to get an idea about the volatility of stock prices. Another way we could use this data would be to predict SBI  stock prices for the next few days by employing machine learning techniques. This would be especially helpful from the shareholder’s point of view.