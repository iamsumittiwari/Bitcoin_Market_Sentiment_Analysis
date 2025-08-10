#Bitcoin Market Sentiment and Trader Performance Analysis


Project Overview
This project explores the relationship between Bitcoin market sentiment and trader performance, using two primary datasets:

Bitcoin Market Sentiment Dataset — Daily sentiment classifications such as Extreme Fear, Fear, Neutral, Greed, and Extreme Greed.

Historical Trader Data from Hyperliquid — Detailed trading records including account, trade size, side, execution price, profit/loss (Closed PnL), fees, and timestamps.

The objective is to analyze how market sentiment affects trader profitability and win rates, identify consistent top performers, and derive actionable insights to guide smarter trading strategies.

Key Features & Analysis
Data preprocessing and merging using date alignment to combine daily market sentiment with individual trades.

Calculation of trading performance metrics by market sentiment, including total trades, average profit, and win rate percentages.

Visualizations such as bar plots for average profit and win rate by sentiment, monthly trends of sentiment and profit, and correlation heatmaps of trading features.

Identification of top performing traders within different sentiment regimes.

Analysis of the impact of trade size and fees on profit/loss across different market sentiments.

Time series analysis showing how shifts in market sentiment correlate with trader profitability over months.

How to Use This Project
Data Setup:
Upload the two CSV files (historical_data.csv and fear_greed_index.csv) to your Google Drive.

Run the Notebook:
The script mounts Google Drive, loads data, processes and merges datasets, and runs all analysis steps with visual outputs.

Explore Outputs:
Review metrics, charts, and summaries to understand the insights on trader behavior across different market sentiments.

Modify or Extend:
You can add further analysis such as risk metrics or model trader performance predictions based on this foundation.

Outcome Summary
Market sentiment significantly influences trader performance, with “Extreme Greed” periods yielding the highest profits and win rates, while “Extreme Fear” phases decrease them. These patterns suggest adapting trading strategies based on prevailing sentiment can improve outcomes. Consistent top traders during various sentiment phases offer valuable strategy insights.

Dependencies
Python 3
Pandas
NumPy
Matplotlib

Seaborn

(Google Colab environment recommended for easy Drive mounting)
