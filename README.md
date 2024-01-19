**Stock Market Prediction**

**Level**: Easy

**Dataset**: https://www.kaggle.com/datasets/luisandresgarcia/stock-market-prediction

**PURPOSE**

Non-professional investors often try to find an interesting stock among those in an index (such as the Standard and Poor's 500, Nasdaq, etc.). They need only one company, the best, and they don't want to fail (perform poorly). So, the metric to optimize is accuracy, described as:

Accuracy = True Positives / (True Positives + False Positives)

And the predictive model can be a binary classifier.

The data covers the price and volume of shares of 31 NASDAQ companies in the year 2022.

**Context**

Every data set I found to predict a stock price (investing) aims to find the price for the next day, and only for that stock.
But in practical terms, people like to find the best stocks to buy from an index and wait a few days hoping to get an increase in the price of this investment.

**Content**

Rows are grouped by companies and their age (newest to oldest) on a common date.
The first column is the company. The following are the age, market, date (separated by year, month, day, hour, minute), share volume, various traditional prices of that share (close, open, high…), some price and volume statistics and target.
The target is mainly defined as 1 when the closing price increases by at least 5% in 5 days (open market days). The target is 0 in any other case.
