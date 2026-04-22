# ACC102 Track2 Assignment: Tech Stock Analysis

## Overview
This project analyzes the monthly performance of three major tech stocks (AAPL, MSFT, GOOGL) using WRDS CRSP monthly stock data from 2025.

## Key Steps
1. **Data Source**: WRDS CRSP Monthly Stock Data
2. **Data Processing**:
   - Converted date column to standard format
   - Pivoted data into a "Date × Stock" table
   - Cleaned missing values
3. **Analysis & Visualization**:
   - Cumulative return trend comparison
   - Annual volatility calculation
   - Average monthly return analysis

## Key Findings
- **Best performer**: GOOGL, with the highest cumulative return
- **Most stable**: AAPL, with the lowest annual volatility (~21.7%)
- **Consistent performer**: MSFT, with steady growth throughout the year

## Tools Used
- Python (Pandas, Matplotlib)
- WRDS CRSP Database
- Jupyter Notebook
