# Machine Learning Stock Earnings Forecast

# Purpose and Hypothesis of the Analysis

## Purpose
At time `t`，using the stock information obtained at `t` and all moments before `t`, forecast the return of the underlying at moment `t+1` relative to moment `t`.

## Hypothesis
Compared to the actual data, the yield prediction results are accurate.

# Required Data
Historical Stock Data from https://tushare.pro/
http://baostock.com/baostock/index.php/Python_API%E6%96%87%E6%A1%A3
http://baostock.com/baostock/index.php/%E6%8C%87%E6%95%B0%E6%95%B0%E6%8D%AE

# Assumed analytical methods
`Logistic regression analysis` of supervised learning


# Process
- Obtain historical stock data for a fixed period of time
- Find or construct predictors
- Use the factors to score the stocks in the stocks pool
- Compare with actual data to test the accuracy of return prediction



# References
- https://bbs.huaweicloud.com/blogs/282278
- https://www.kaggle.com/code/bryanb/stock-prices-forecasting-with-lstm