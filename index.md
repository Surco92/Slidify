---
title: "S&P 500"
author: ""
highlighter: highlight.js
output:
  html_document:
     keep_md: yes
job: null
knit: slidify::knit2slides
mode: selfcontained
hitheme: tomorrow
subtitle: Simple Moving Average
framework: io2012
widgets: []
--- 


## S&P500 

- Stock market index of 500 large companies listed on NASDAQ and NYSE.
- Based on market capitalizations of companies
- One of the best representations of the U.S. stock market

## Simple Moving Average (SMA)
- One of the most basic indicators for technical analysis of financial data
- Calculated by adding the closing price of the security for a number of time periods and then dividing this total by the number of time periods
- Goal is to predict the direction of prices.
- SMA computed using low number of periods is more sensitive but also prone to error
- Easy to interpret but SMA alone is not enought for accurate predictions

---

## S&P500 chart with 150 period SMA


```
## [1] "GSPC"
```

<img src="assets/fig/unnamed-chunk-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" />

---

## Trading Strategy

* Price crosses the moving average
  - Signalise the reversal of the trend
  - Price will continue in the direction of the crossing 
* Price bounces of the moving average
 -  Means that price will continue to follow the current trend for some time
* Very often crossing turns out to be bounce of and vice versa
* To reduce risk, analysts often use several Moving Averages computed form different number of periods

---

## References

- S&P500 Index: http://en.wikipedia.org/wiki/S%26P_500
- Moving Average: http://www.investopedia.com/terms/m/movingaverage.asp
- Quantmod: http://www.quantmod.com/
