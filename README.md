# SoC-Developing-Trading-Strategy-with-Pine-Script

This repository contains my scripts for various Trading Indicators and Strategies, written in Pine Script on Trading View, as a part of Seasons of Code (SoC) 2023 conducted by the Web and Coding Club (WnCC), IIT Bombay. 

## Technical Analysis
Technical analysis is a financial trading discipline employing patterns in market data to analyse trends, identify trading opportunities and make predictions. Two major types of technical analysis are:
- Chart Patterns
- Technical (Statistical) Indicators

Some of the popular technical [indicators](./Indicators) include Moving average convergence divergence (MACD) and Relative strength index (RSI). In this project, a few technical indicators have been scripted in Pine Script, and can also be compared with chart patterns by running the scripts on a platform such as [TradingView](https://www.tradingview.com/pine/). 

### [Indicators](./Indicators):
- [Moving Average Convergence Divergence](./Indicators/MACD.pine)
- [Simple Moving Average and Exponential Moving Average](./Indicators/EMA_SMA.pine)
- [Bollinger Band](./Indicators/Bollinger_Band.pine)
- [Intraday Gap Detector](./Indicators/Intraday_Gap_Detector.pine)

### [Strategies](./Strategies):
- [Dead Cross Over](./Strategies/Dead_Cross_Over.pine): The "death cross" is a market chart pattern reflecting recent price weakness. It refers to the drop of a short-term moving average—meaning the average of recent closing prices for a stock, stock index, commodity or cryptocurrency over a set period of time—below a longer-term moving average.
- [Swing Trade](./Strategies/Swing_Trade.pine)
- [5 EMA Strategy: Power of Stocks](./Strategies/5EMA.pine)
- [Bollinger Band Strategy](./Strategies/Bollinger_Band_Strategy.pine)

### [Signals](./Signals):
- [Inside Candle Detector](./Signals/Inside_Candle_Detector.pine)
