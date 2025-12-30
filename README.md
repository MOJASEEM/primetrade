# README - Trading Data & Sentiment Analysis

## Project Overview
Analysis of 211,224 cryptocurrency trades from Hyperliquid platform correlated with 2,644 daily Bitcoin Fear & Greed Index records using Notebook 1 (EDA & Preprocessing).

## Datasets
1. **Trading Data**: 211,224 trades with Account, Coin, Price, Size, PnL, Fees
2. **Sentiment Data**: 2,644 daily records with Fear & Greed Index (0-100)

## Analysis Performed

### Data Processing
- ✅ Loaded and validated both datasets
- ✅ Converted timestamps and parsed dates
- ✅ Created features: is_profitable, pnl_roi, fee_impact
- ✅ Calculated trader-level metrics (PnL, win rate, trade count)
- ✅ Aggregated daily metrics
- ✅ Merged sentiment with trading data

### Key Calculations
- **Trader Metrics**: Total PnL, avg PnL, win rate, trade count per account
- **Daily Metrics**: Daily PnL, win rate, active traders, total volume
- **Statistical Tests**: Fear vs Greed comparison with p-values
- **Correlations**: Sentiment index vs daily PnL

## Output Files

### CSV Files (4)
- `sentiment_processed.csv` - Cleaned sentiment data
- `trader_metrics.csv` - Trader statistics
- `daily_metrics.csv` - Daily aggregated metrics
- `merged_sentiment_trading.csv` - Combined dataset

### Visualizations (3)
- `sentiment_analysis.png` - Sentiment timeline & distribution
- `daily_metrics.png` - 3-panel daily trends
- `sentiment_trader_analysis.png` - 4-panel comparison

## Key Findings
- [To be filled from Notebook 1 output]
- Fear vs Greed performance difference: $[amount]
- Statistical significance: p-value [value]
- Correlation (Sentiment vs PnL): r = [value]

## Data Quality
✅ No missing values  
✅ All types converted correctly  
✅ [X] traders analyzed  
✅ [X] overlapping days  

## Usage
All outputs ready for advanced analysis in Notebook 2. CSV files can be used for further statistical testing, clustering, and predictive modeling.

---
**Status**: Notebook 1 Complete ✅  
**Date**: December 2024
