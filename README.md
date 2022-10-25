# Identify and analyze stock price trends using financial quantitative averaging system trading strategies

# Purpose and Hypothesis of the Analysis

## Purpose
Identify and analyze stock price trends by using the most common method of capturing trends, the moving average

## Hypothesis
Buying on a buy signal and selling on the next sell signal will definitely be gain.

# Required Data

Historical Stock Data from https://tushare.pro/

# Assumed analytical methods

Double SMA(Simple Moving Average) Crossing Strategy:
- Create the short-term average and the long-term average
- A buy signal is released when the short-term SMA crosses the long-term SMA from the bottom up.
- A sell signal is released when the short-term SMA crosses the long-term SMA from above and below.


<!-- Weighted Moving Average, WMA？ -->
<!-- Exponential Moving Average, EXPMA or EMA？ -->

# Process
## Create SMA strategy, creates new SMA-30 and SMA-100 information

SMA-30 is the Short Moving Average of 30 days and SMA-100 is Short Moving Average of 100 days.

## Graph the results, as well as see the date of the price of the buy or sell option


## Get the earnings between a buy signal and the next sell signal

## SMAの日数を変更し、どういう日数であれば収益が最大になるのかを検証

## 企業ごと・業界ごとなどで特徴あればまとめる

# References
- https://bbs.huaweicloud.com/blogs/282278
- https://www.google.com/search?q=python+running+average SMA
- https://blog.csdn.net/weixin_26746401/article/details/108260150
- https://blog.csdn.net/weixin_26735933/article/details/108925217
- https://developer.aliyun.com/article/889676#slide-16