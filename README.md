# TCS Stock Data Analysis

This project analyzes the provided TCS stock datasets and builds a simple next-day closing price prediction workflow.

## Files

- `project3` - main Python analysis script
- `TCS_stock_history.csv` - historical OHLCV data
- `TCS_stock_action.csv` - dividend and stock split events
- `TCS_stock_info.csv` - company metadata

## What the script does

- loads and cleans the TCS datasets
- computes technical features such as moving averages and volatility
- compares Linear Regression, Random Forest, and Gradient Boosting
- saves plots and a summary report under `tcs_outputs/`

## Run

Use the installed Anaconda Python from this workspace:

```powershell
& 'C:\Users\pc\anaconda3\python.exe' project3
```

## Notes

- The project was prepared from the TCS PDF brief and the CSV files you provided.
- The generated outputs are intended for GitHub submission and local review.