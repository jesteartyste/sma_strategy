# sma_strategy


Welcome in SMA strategy testing notebooks!

You can find 2 files in this repo:

SMA_strategy.ipynb - gives you evaluation of SMA crossover strategy with entry variables decided by user. As the final ouput, user gets information about how his strategy performed in given time period, in terms of percentage change.
User need to provide:
- ticker
- start of backtetsing period
- end of backtesting period
- ticker timeframe interval
- period for fast sma
- period for slow sma
- laverage
- position size



ticker_list_ml.ipynb - model that gives user best possible configuration of SMA fast and slow indicators for best performance, in terms of percentage change, on choosen tickers.
User need to provide:
- ticker list
- start of backtetsing period
- end of backtesting period
- ticker timeframe interval


Libraries used:
- pandas
- pandas-ta
- numpy
- yfinance
- matplotlib
