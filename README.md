# Bitcoin Market Sentiment & Trader Behavior Analysis

## Project Overview
This project analyzes how Bitcoin market sentiment (Fear/Greed) impacts trader behavior and performance on Hyperliquid. Using historical trader data and daily sentiment indices, we explore trade size, win rate, trade frequency, and long/short bias. The goal is to uncover actionable insights to inform smarter trading strategies.

## Datasets
1. **Bitcoin Market Sentiment (Fear/Greed)**  
   - Columns: Date, Classification (Fear / Greed / Extreme Fear / Extreme Greed / Neutral), Value, Sentiment Score  
2. **Historical Trader Data (Hyperliquid)**  
   - Columns: Account, Symbol, Execution Price, Size USD, Side (BUY/SELL), Closed PnL, Timestamp, etc.

## Setup Instructions
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/bitcoin-market-sentiment.git
jupyter notebook notebook.ipynb.


Methodology

Load and clean both datasets; convert timestamps to dates.

Merge sentiment and trader data on a daily level.

Create key metrics:

Daily PnL per trader

Win rate and average trade size

Number of trades per day

Long/short trade ratio

Analyze metrics vs sentiment to identify patterns.

Segment traders: frequent vs infrequent, consistent vs inconsistent.

Derive actionable strategies and optional predictive modeling/clustering.



Key Insights

Traders take larger trades during Extreme Greed, but win rates drop → risk of overconfidence.

Long trades dominate in Greed, short trades in Fear → adjust positions accordingly.

Consistent winners maintain stable PnL regardless of market sentiment; inconsistent traders face higher volatility.

Strategy Recommendations

Reduce trade size during Extreme Greed to mitigate risk.

Focus on selective long trades during Fear days for safer returns.

Adjust trading behavior based on trader segment: frequent/infrequent, consistent/inconsistent.



Output

All charts and tables are saved in the output/ folder, including:

PnL by sentiment

Win rate by sentiment

Trade size and frequency metrics

Long/short ratio charts
