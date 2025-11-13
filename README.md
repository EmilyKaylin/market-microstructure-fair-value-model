The goal of this project is to construct and evaluate fair-value price estimators using high-frequency Australian equity data, focusing on:
- Synchronous trade–quote alignment (merge_asof)
- Efficient price estimation using L1 mid, bid, ask, and depth-based variants
- Microstructure noise diagnostics (bid–ask bounce, stale quotes, autocorrelation)
- Intraday variation via early / midday / close phase windows
- Statistical accuracy: MAE, RMSE, correlation and scatter diagnostics
- Robust inference techniques (White/Newey–West standard errors)

The analysis demonstrates how different market microstructure features affect the relationship between observed prices and underlying fair value.
