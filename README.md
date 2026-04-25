# ACC102 Track 2: Tech Stock Monthly Performance Analysis

## 1. Problem & User
This project analyzes the monthly risk and return performance of three major U.S. tech stocks: AAPL, MSFT, GOOGL.
The intended audience includes finance students, instructors, and potential investors interested in empirical stock performance.

## 2. Data
- Source: WRDS CRSP Monthly Stock Database (2025)
- Access date: April 2026
- Key fields: Ticker, Monthly Date, Monthly Price

## 3. Methods (Main Python Steps)
1. Load and clean monthly stock data
2. Convert date to datetime format
3. Calculate monthly returns and cumulative returns
4. Compute annualized volatility
5. Visualize performance trends using Matplotlib

## 4. Key Findings
- GOOGL achieved the **highest cumulative return** in 2025.
- AAPL showed the **lowest volatility**, making it the most stable stock.
- MSFT delivered steady and consistent growth throughout the year.
- All three stocks exhibited positive annual returns.

## 5. How to Run
1. Open the Jupyter Notebook (.ipynb) file
2. Run all cells sequentially
3. View output tables, return metrics, and plots directly in the notebook

## 6. Product Link / Demo
GitHub Repository: https://github.com/MINYULI1101/ACC102-Track2/blob/main/ACC102_Track2_WRDS_Analysis_liminyu.ipynb
Demo Video: 

## 7. Limitations & Next Steps
- Limitations: Only 12 months of data; no macroeconomic factors included.
- Improvements: Extend data period, add more stocks, include Sharpe ratio, and build interactive charts.
