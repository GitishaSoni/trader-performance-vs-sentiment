# Trader-performance-vs-sentiment
An end-to-end analysis of how Fear/Greed market sentiment impacts trader behavior and performance on Hyperliquid, with data-backed insights, trader segmentation, and actionable strategy recommendations.

# Trader Performance vs Market Sentiment

## Objective
Analyze how market sentiment (Fear/Greed) impacts trader behavior and performance on Hyperliquid. The goal is to identify behavioral patterns and derive actionable strategy recommendations.

---

## Datasets
1. **Bitcoin Market Sentiment**
   - Daily sentiment labels (Fear, Extreme Fear, Neutral, Greed, Extreme Greed)

2. **Hyperliquid Trader Data**
   - Execution-level trading data including account, timestamp, trade size, side, and PnL

---

## Methodology
- Performed data quality checks (missing values, duplicates)
- Aligned trade data with daily market sentiment
- Engineered key performance and behavior metrics:
  - Daily PnL per trader
  - Win rate
  - Trade frequency
  - Long/Short bias
  - Exposure (using trade size as a proxy)
- Conducted sentiment-based performance analysis
- Segmented traders based on behavior and outcomes
- Derived actionable trading strategies

---

## Key Insights
- Trader performance varies significantly across Fear and Greed regimes
- Greed periods show higher win rates but increased volatility
- Frequent traders exhibit higher PnL dispersion, indicating overtrading risk
- Consistent winners outperform other traders across sentiment regimes
- High exposure traders assume greater downside risk via larger trade sizes

---

## Strategy Recommendations
- Reduce exposure and trading frequency during Fear regimes
- Allow selective aggression during Greed regimes only for consistent traders
- Allocate capital based on trader segment rather than uniformly

---

## How to Run
1. Open the notebook in Jupyter or Google Colab
2. Upload the required CSV datasets
3. Run all cells sequentially

---

## Environment
- Python 3.x
- pandas, numpy
- matplotlib, seaborn, plotly
- scikit-learn (for optional bonus analysis)
