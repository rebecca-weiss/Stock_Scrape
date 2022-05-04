# Stock Scrape
#### Author: Rebecca Weiss

## Purpose
R package to scrape / clean historical stock prices

## Usage
To scrape data, use `scrapestock` function with the url to historical data. 
For example:
Use function to get data from Apple, Tesla, Amazon, and Netflix
```{r}
tsla <- scrapestock('https://finance.yahoo.com/quote/TSLA/history?p=TSLA')
aapl <- scrapestock('https://finance.yahoo.com/quote/AAPL/history?p=AAPL')
nflx <- scrapestock('https://finance.yahoo.com/quote/NFLX/history?p=NFLX')
amzn <- scrapestock('https://finance.yahoo.com/quote/AMZN/history?p=AMZN')
```
