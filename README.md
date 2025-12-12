# Stock-Market-Analysis-In-Tableau
Python (Pandas) + Tableau | Feature Engineering + Interactive Visualization

This project is an end-to-end stock market analysis workflow where I engineered key trading indicators using Pandas and transformed the data into an interactive Tableau dashboard for trend, volume, and momentum analysis.

Instead of relying on pre-built indicators, I generated everything from scratch — cleaner pipeline, cleaner insights.

🔍 Project Overview

The goal was simple:
Turn raw stock price data into a decision-ready, visual analytics dashboard.

I used Python to preprocess and enrich the dataset with custom indicators, then exported the cleaned CSVs into Tableau to build an interactive dashboard capable of spotting:

Trend direction

Momentum shifts

Price breakouts

Volume surges

SMA crossovers (50 vs 200)

🧰 Tools & Technologies

Python (Pandas, NumPy)

Tableau Desktop

CSV Data Pipeline

Feature Engineering & Data Cleaning

Dataset source:
👉 https://www.kaggle.com/datasets/jacksoncrow/stock-market-dataset

🧪 Data Engineering

Using Pandas, I created new analytical columns to support trend and momentum analysis:

✔ 50-Day Moving Average
✔ 200-Day Moving Average
✔ Percent Change in Price
✔ Percent Change in Volume
✔ Cleaned Date/Index Structure
✔ Exported CSV Files for Tableau

These engineered features allowed for deeper insights beyond raw OHLC data.

📊 Tableau Dashboard Features

The Tableau dashboard includes:

Interactive stock selection

Moving average comparison (50 MA vs 200 MA)

Price & volume momentum tracking

Trend visualization across time

Highlighted crossover events

Dynamic filters

This setup enables quick interpretation of market structure across multiple tickers.
