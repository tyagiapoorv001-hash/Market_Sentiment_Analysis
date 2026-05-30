# Bitcoin Market Sentiment and Trader Behavior Analysis

This project analyzes how Bitcoin market sentiment, such as Fear and Greed, relates to trader behavior and performance on Hyperliquid.

## Project Overview

The analysis studies how sentiment conditions affect:

- Daily profit and loss
- Win rate
- Trade size
- Trade frequency
- Long and short trading bias

The goal is to identify patterns that can support better risk management and trading decisions.

## Project Structure

```text
Market_Sentiment_Analysis/
|-- market_sentiment_analysis.ipynb
|-- fear_greed_index.csv
|-- requirements.txt
`-- README.md
```

## Dataset

The project uses Bitcoin Fear and Greed sentiment data and trader behavior/performance data.

Important fields include:

- Date
- Sentiment classification
- Sentiment score
- Trade side
- Trade size
- Closed PnL
- Trade timestamp

## Methodology

1. Load and clean market sentiment and trader data.
2. Convert timestamps into daily dates.
3. Merge sentiment and trader activity by date.
4. Calculate daily trading metrics.
5. Compare trader performance across sentiment categories.
6. Derive insights and risk-control recommendations.

## Key Insights

- Traders tend to take larger trades during high-greed conditions.
- Win rate can fall during overconfident market phases.
- Long trades are more common during greed phases, while fear phases can increase short bias.
- Consistent traders show more stable performance across sentiment conditions.

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook "market_sentiment_analysis.ipynb"
```

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

