# Prime Indicator Lab

Open `index.html` in a browser. The TradingView chart is an external embed and needs internet access.

Signal calculations require a CSV of real, closed OHLCV candles with these columns:

```csv
time,open,high,low,close,volume
```

The CSV stays in the browser. No sample prices are generated. The displayed signal model is a transparent local approximation based on the UI evidence provided; it is not Guardeer Prime's private formula. DOM, true bid/ask delta, footprint/absorption, verified calendar data, and cross-device AWS signal synchronization need their respective authenticated data sources and are not implemented in this standalone project.
