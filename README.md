Developed by: **Erenali Balcıkardeşler**
# MT5 Trading Bot

## Indicators

### ALMA_v1.02.mq5
This indicator implements the Arnaud Legoux Moving Average (ALMA) with a dual-slope filter.
It visually highlights trend direction:

- **Lime**: Strong bullish slope
- **Red**: Strong bearish slope
- **Gray**: Neutral / sideways

### Innovation: Adaptive Trend Detection
Enhanced the standard ALMA indicator with:
- **Dual-timeframe slope analysis** (30 & 150 periods)
- **Robust threshold calculation** using Median Absolute Deviation
- **Dynamic signal generation** with adaptive noise filtering

### Mathematical Foundation
- **Gaussian kernel smoothing** for price data
- **Statistical robustness** against market noise
- **Multi-scale analysis** for trend confirmation

### Technical Implementation
- Optimized weight calculation with caching
- Real-time slope analysis with dual thresholds
- Color-coded visualization for immediate trend identification

### Applications in Quantitative Finance
This indicator demonstrates advanced signal processing techniques applicable to:
- Factor model development
- Regime detection systems
- Risk-adjusted alpha generation
