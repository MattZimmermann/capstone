# capstone
Can we beat the market using machine learning?

This project was created to gain an insight on how machine learning can help increase investment returns. We gather data from Yahoo Finance, do some exploratory data analysis on the given stock, create two models and compare the results to find the best one, and then finally use those predicted values to try and beat a traditional buy and hold strategy. This project can help get a better understanding on how we can utilize model results to make more informed trades in the stock market.

Packages that may require installation:
- Yfinance 'pip install yfinance --upgrade --no-cache-dir'
- Tensorflow 'pip install tensorflow'

To use this project the variable 'tick' needs to be updated to any stock on Yahoo Finance. The rest of the code is automated to work with eachother, so once the ticker is updated, the code should operate correctly. The results of each ticker may vary drastically, so in no way does this project work for every stock, in every timeframe.

Some of the code was influenced/taken from Professor Tweneboah's Machine Learning course. There was an in-class assignment that analyzed timseries data using ARIMA and LSTM models. Both the LSTM and ARIMA model code was influenced, but not taken from this assignment. However, the 'Stationarity Test' code was taken, but not in its entirety.
All other code was produced by me using various documentation on the packages and or prior knowledge of code.

All of the code for my project can be found in the blog.qmd file, however a different version of the code producing every plot of a chosen stock can be found in my 'project.ipynb' file located at, 'code/project.ipynb'.