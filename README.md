# Trader Performance vs Market Sentiment
**Primetrade.ai Data Science Intern Assignment**

## Overview
Analysis of how Bitcoin market sentiment (Fear/Greed) affects trader 
behavior and performance on Hyperliquid.

## Datasets
- historical_data.csv — 4,658 trades from 3 Hyperliquid accounts (Sep 2024 – Apr 2025)
- fear_greed_index.csv — Daily Bitcoin Fear/Greed index

## How to Run
1. Open Trader_Sentiment_Analysis.ipynb in Google Colab
2. Upload both CSV files to the Colab session
3. Run all cells in order

## Key Insights
1. Fear days produce 4x higher avg PnL than Greed days ($7,849 vs $1,794)
2. Traders go fully short with larger position sizes during Fear days
3. Each trader has a unique sentiment edge — Trader 1 peaks on Fear days,
   Trader 2 on Greed days, Trader 3 on Neutral days

## Trader Archetypes (Clustering)
- High Volume Trader — 127 trades/day, largest position sizes
- Consistent Trader — low volume but most active across days
- High Win Rate Trader — best win rate at 30%

## Predictive Model
Random Forest model predicts profitable days with 94% accuracy.
Top features: win rate (67%), trade count (14%), sentiment (2%).

## Strategy Recommendations
1. During Fear days: increase size and bias toward short positions
2. Identify which sentiment regime you perform best in and scale up only then

## Tools
Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Google Colab

## Overview
Analysis of how Bitcoin market sentiment (Fear/Greed) affects trader 
behavior and performance on Hyperliquid.

## Datasets
- historical_data.csv - 4,658 trades from 3 Hyperliquid accounts (Sep 2024 – Apr 2025)
- fear_greed_index.csv - Daily Bitcoin Fear/Greed index

## How to Run
1. Open Trader_Sentiment_Analysis.ipynb in Google Colab
2. Upload both CSV files to the Colab session
3. Run all cells in order

## Key Insights
1. Fear days produce 4x higher avg PnL than Greed days ($7,849 vs $1,794)
2. Traders go fully short with larger position sizes during Fear days
3. Each trader has a unique sentiment edge - Trader 1 peaks on Fear days,
   Trader 2 on Greed days, Trader 3 on Neutral days

## Trader Archetypes (Clustering)
- High Volume Trader — 127 trades/day, largest position sizes
- Consistent Trader — low volume but most active across days
- High Win Rate Trader — best win rate at 30%

## Predictive Model
Random Forest model predicts profitable days with 94% accuracy.
Top features: win rate (67%), trade count (14%), sentiment (2%).

## Strategy Recommendations
1. During Fear days: increase size and bias toward short positions
2. Identify which sentiment regime you perform best in and scale up only then

## Tools
Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Google Colab
