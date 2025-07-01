#  Multi-Factor Stock Ranking Engine (Nifty50)

This project simulates a quantitative stock scoring system, ranking Nifty50 stocks based on valuation and momentum factors.
##  Highlights

- Uses realistic snapshot of Nifty50 stock data
- Calculates a multi-factor score: `(daily change %) / P/E ratio`
- Ranks stocks and visualizes top 10
- Easily deployable as a Kaggle notebook or Streamlit app

## Scoring Logic
-score = (daily % price change) / (P/E ratio)
This allows high-momentum, undervalued stocks to rank higher.

##  Project Structure

multi-factor-stock-ranking-engine/
├── analysis.ipynb ← Main notebook (exported from Kaggle)
├── nifty50_factors.csv ← Sample Nifty50 data used
├── README.md ← This file
└── screenshots/ ← Optional: bar/scatter plots


##  Sample Visuals

- Scatter Plot: P/E vs Daily % Change (sized by Market Cap)
- Bar Chart: Top 10 stocks by multi-factor score

## Tech Stack

- Python (pandas, seaborn, matplotlib)
- Jupyter / Kaggle notebook
- CSV dataset (no live API needed)

##  Notes

This project does not use live data due to NSE and Alpha Vantage limitations. The dataset simulates a recent snapshot for demonstrative purposes.



