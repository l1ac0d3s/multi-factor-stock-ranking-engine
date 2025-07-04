#  Multi-Factor Stock Ranking Engine (Nifty50)

This project simulates a quantitative stock scoring system, ranking Nifty50 stocks based on valuation and momentum factors.
##  Highlights

-Uses a realistic snapshot of Nifty50 stock data (CSV)
-Computes a custom multi-factor score:
Score = (Daily % Price Change) / (P/E Ratio)
-Identifies undervalued, high-momentum stocks
-Visualizes the Top 10 stocks by score
-Includes credit rating logic (AAA to BB)
-Easily runnable on Kaggle, Colab, or Jupyter
-Ready to be deployed as a Streamlit App


## Scoring Logic
Multi-Factor Score = (Daily % Price Change) / (P/E Ratio)

This logic rewards:
Momentum: Positive daily price movement
Valuation: Lower P/E ratios (undervalued stocks)
Higher scores indicate better combined momentum and valuation.

##  Project Structure

multi-factor-stock-ranking-engine/
├── analysis.ipynb ← Main notebook (exported from Kaggle)
├── nifty50_factors.csv ← Sample Nifty50 data used
├── README.md ← This file
└── screenshots/ ← Optional: bar/scatter plots


##  Sample Visuals

-Bar Chart: Top 10 stocks by multi-factor score
-Pie Chart: Credit rating distribution
-Scatter Plot: P/E Ratio vs Daily % Change (sized by Market Cap)

## Tech Stack

-Python: pandas, matplotlib, seaborn
-Notebook: Jupyter, Kaggle, Google Colab
-Data: Static CSV (no API required)


##  Disclaimer

-This project uses a simulated snapshot of Nifty50 data.
-No live market API (e.g., NSE, Alpha Vantage) is used.
-Results are for educational/demonstration purposes only and not financial advice.



