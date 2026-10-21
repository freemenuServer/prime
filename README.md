# Prime Indicator Lab

Open `index.html` in a browser. The TradingView chart is an external embed and needs internet access. BTC/ETH selections also request public Binance candle history and connect to its public kline stream; signals recalculate on closed candles.

For XAU/USD and EUR/USD, signal calculations require a CSV of real, closed OHLCV candles with these columns:

```csv
time,open,high,low,close,volume
```

The CSV stays in the browser. No sample prices are generated. The 56-rule score is a local implementation of standard indicator/price-action definitions, not Guardeer Prime's private formula. Crypto candles use public Binance market-data endpoints; XAU/FX credentials or a verified feed were not provided. DOM, true bid/ask delta, footprint/absorption, verified calendar data, and cross-device AWS signal synchronization need their respective data sources and are not implemented in this standalone project.
