
## Mean Reversion and Z-Score Reversion Trading Strategies

This project implements and visualizes mean reversion and Z-score reversion trading strategies using historical adjusted close prices for the stocks of **Apple Inc. (AAPL)** and the **SPDR S&P 500 ETF Trust (SPY)**. The strategies are applied to data fetched from Yahoo Finance.

### Overview

1. **Data Download**: Historical adjusted close prices for AAPL and SPY are downloaded using the `yfinance` library.
2. **Rolling Statistics**: Calculates rolling mean and standard deviation for a 20-day window.
3. **Signal Generation**:
   - **Simple Mean Reversion**: Generates buy and sell signals based on whether the current price is above or below the rolling mean.
   - **Z-Score Reversion**: Generates buy and sell signals based on Z-scores, where thresholds determine trading actions.
4. **Visualization**: Plots the price data, rolling means, and generated trading signals to visualize the strategies.

### Requirements

- Python 3.x
- `yfinance`
- `pandas`
- `numpy`
- `matplotlib`

You can install the required libraries using pip:

```bash
pip install yfinance pandas numpy matplotlib
```

### Usage

1. **Download Historical Data**: Fetches adjusted close prices for AAPL and SPY from Yahoo Finance.
2. **Calculate Rolling Statistics**: Computes 20-day rolling mean and standard deviation.
3. **Generate Trading Signals**:
   - **Simple Mean Reversion**: Buy when the price is below the rolling mean and sell when it is above.
   - **Z-Score Reversion**: Buy or sell based on the Z-score crossing specified thresholds.
4. **Plot Results**: Visualizes the price data, rolling means, and trading signals for both strategies.

### Contributing

Feel free to open issues or submit pull requests if you have suggestions for improvements or additional features.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
