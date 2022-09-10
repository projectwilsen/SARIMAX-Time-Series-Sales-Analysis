# Shopee Sales Prediction

In this cases, I am challenged my self by predicting upcoming sales of my business (Abang Stiker). I have downloaded 2 years data record of my sales in Shopee, and pre processed it using Excel and Python. Since this is my first time series project, I tried to make it more simple by selecting only two variables which are date and sales. In my opinion, there are 2 important things in this project:

1. Checking the stationary of our data using Dickey Fuller Test
2. Analyzing the trend by asking "Is there seasonality or not?"

Since, my data is indicating a seasonality, I have decided to using SARIMAX ( Seasonal Autoregressive Integrated Moving Average) method. Otherwise, if the data does not indicate seasonality, we probably can use ARIMA method to get higher accuracy. What I have done here is still far from perfect, there are some points that predicted either higher or lower than the exact value. Let me know, if you guys having a great suggestion for what should I improve in this code to get a better prediction. Cheers!
