# SoC-Developing-Trading-Strategy-with-Pine-Script

This repository contains my scripts for various Trading Indicators and Strategies, written in Pine Script on Trading View, as a part of Seasons of Code (SoC) 2023 conducted by the Web and Coding Club (WnCC), IIT Bombay. 

## Technical Analysis
Technical analysis is a financial trading discipline employing patterns in market data to analyse trends, identify trading opportunities and make predictions. Two major types of technical analysis are:
- Chart Patterns
- Technical (Statistical) Indicators

Some of the popular technical [indicators](./Indicators) include Moving average convergence divergence (MACD) and Relative strength index (RSI). In this project, a few technical indicators have been scripted in Pine Script, and can also be compared with chart patterns by running the scripts on a platform such as [TradingView](https://www.tradingview.com/pine/). 

### [Indicators](./Indicators):
- [Moving Average Convergence Divergence](./Indicators/MACD.pine): Moving average convergence/divergence (MACD, or MAC-D) is a trend-following momentum indicator that shows the relationship between two exponential moving averages (EMAs) of a security’s price. The MACD line is calculated by subtracting the 26-period EMA from the 12-period EMA. 
- [Simple Moving Average and Exponential Moving Average](./Indicators/EMA_SMA.pine): A simple moving average (SMA) calculates the average of a selected range of prices, usually closing prices, by the number of periods in that range.
- [Bollinger Band](./Indicators/Bollinger_Band.pine): Bollinger Bands are a type of chart indicator for technical analysis and have become widely used by traders in many markets, including stocks, futures, and currencies.
- [Intraday Gap Detector](./Indicators/Intraday_Gap_Detector.pine): For intraday gap trading strategies we look for price gaps in the opening price of the trading day compared to the previous day's closing price.

### [Strategies](./Strategies):
- [Dead Cross Over](./Strategies/Dead_Cross_Over.pine): The "death cross" is a market chart pattern reflecting recent price weakness. It refers to the drop of a short-term moving average—meaning the average of recent closing prices for a stock, stock index, commodity or cryptocurrency over a set period of time—below a longer-term moving average.
- [Swing Trade](./Strategies/Swing_Trade.pine): Swing trading is a style of trading that attempts to capture short- to medium-term gains in a stock (or any financial instrument) over a period of a few days to several weeks. It involves taking trades that last a couple of days up to several months in order to profit from an anticipated price move.
- [5 EMA Strategy: Power of Stocks](./Strategies/5EMA.pine): 5 EMA Strategy by Power of Stocks.
- [Bollinger Band Strategy](./Strategies/Bollinger_Band_Strategy.pine): A Bollinger Band is a technical analysis tool defined by a set of trendlines. They are plotted as two standard deviations, both positively and negatively, away from a simple moving average (SMA) of a security's price and can be adjusted to user preferences. 

### [Signals](./Signals):
- [Inside Candle Detector](./Signals/Inside_Candle_Detector.pine): Inside bars occur when the range of a candlestick falls entirely within the previous candlestick's range.

### [Custom Strategies](./Custom_Strategies):
- [My Strategy 1](./Custom_Strategies/My_Strategy_1.pine): My Custom Strategy 1
- [My Strategy 2](./Custom_Strategies/My_Strategy_2.pine): My Custom Strategy 2
