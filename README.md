# Trader Performance vs Market Sentiment Analysis

## Objective
Analyze how Bitcoin market sentiment (Fear vs Greed) impacts trader behavior and performance on Hyperliquid.

## Datasets
- Bitcoin Fear & Greed Index
- Hyperliquid historical trader dataset

## Methodology
- Converted timestamps to daily level
- Created daily trader metrics:
  - Daily PnL
  - Win rate
  - Trade frequency
  - Average trade size
  - Long/Short ratio
- Merged trader metrics with sentiment classification
- Performed segment-based analysis

## Key Insights
1. Trader profitability differs across Fear and Greed regimes.
2. Trade behavior (frequency, positioning) adapts to sentiment conditions.
3. High-activity traders show amplified performance variance.
4. Consistent traders maintain stable outcomes across cycles.

## Strategy Recommendations
- Reduce leverage during Fear periods for high-volatility traders.
- Increase exposure selectively during Greed for high win-rate traders.
- Implement activity filters to prevent overtrading in volatile sentiment regimes.

## How to Run
1. Install requirements:
