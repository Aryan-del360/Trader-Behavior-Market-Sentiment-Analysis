# Trader Behavior & Market Sentiment Analysis

## Project Overview
This project explores the relationship between **trader behavior** and **market sentiment** (Fear vs Greed) using:
- **Historical Trader Data from Hyperliquid**
- **Bitcoin Fear & Greed Index**

The goal is to identify patterns in profitability, leverage, risk, and trading activity under different market sentiment phases.

---

## Project Structure
```
ds_Shubham/
├── notebook_1.ipynb        # Main analysis (Google Colab)
├── csv_files/              # Raw & processed CSV files
│   └── historical_data.csv
│   └── fear_greed_index.csv
│   └── daily_trades_merged.csv
├── outputs/                # Visual outputs (charts/plots)
│   └── fear_greed_vs_volume.png
│   └── pnl_by_sentiment.png
│   └── volume_trend.png
├── ds_report.pdf           # Final summarized report
└── README.md               # Setup instructions & project notes
```

---

## Steps Performed
1. **Data Cleaning**
   - Standardized column names.
   - Converted timestamps to proper datetime format.
   - Converted numeric fields (prices, sizes, pnl, fee).

2. **Feature Engineering**
   - Daily aggregation of trades: total volume, total trades, median PnL, win rate.
   - As-of merge with Fear & Greed dataset.

3. **Exploratory Data Analysis**
   - Trends in daily trading activity.
   - Distribution of win rates and profitability.
   - Comparison of behavior during Fear vs Greed periods.

4. **Insights**
   - Traders were active between 2023-2025 with ~480 aligned records.
   - PnL and win rates show variations depending on sentiment phase.
   - Trading volume is not always strongly correlated with the sentiment index.

---

## How to Run
- Open notebooks (`notebook_1.ipynb`) in **Google Colab**.
- Upload Datasets and update file paths as required.
- Run all cells to reproduce analysis and outputs.

---

## Deliverables
- **ds_report.pdf** → Short professional summary of findings.
- **README.md** → Setup guide and notes.
- **Outputs** → Charts/visuals supporting analysis.
- **GitHub Repo** → Final submission with the same structure.

---

## Candidate
Shubham Sharma
