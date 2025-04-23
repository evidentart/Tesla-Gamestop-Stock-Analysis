# Tesla & GameStop Stock Analysis

This project is a personal exploration of stock performance and financial trends of **Tesla (TSLA)** and **GameStop (GME)** using historical stock data and quarterly revenue data. It combines financial data extraction, web scraping, and data visualization to provide a clear picture of each company's trajectory over time.

---

## Overview

I wanted to understand how major companies like Tesla and GameStop have evolved over recent years — both in stock price and revenue. This project uses Python tools like `yfinance`, `BeautifulSoup`, and `Plotly` to:

- Extract historical stock data
- Scrape revenue data from Macrotrends
- Create interactive graphs showing stock performance vs. revenue
- Export visualizations and organize them for review and sharing

---

## Tools & Libraries

- `pandas` – Data manipulation
- `yfinance` – Stock data retrieval
- `requests` + `BeautifulSoup` – Web scraping revenue data
- `plotly` – Interactive graphing
- `Jupyter Notebook` – Development environment

---

## Visualizations

Both Tesla and GameStop data are plotted using Plotly for an interactive experience. These charts compare:

- Share price trends over time
- Quarterly revenue over the same period

Due to GitHub’s limitations, interactive Plotly charts aren't viewable directly inside notebooks on GitHub, so static screenshots are included in the folder. The interactive versions open in your browser when running the notebook locally.

---

## Key Highlights

- Fetched and processed historical stock data from Yahoo Finance
- Cleaned and formatted scraped revenue data
- Built a reusable function `make_graph()` to visualize both datasets in a dual-subplot format
- Organized all outputs for easy navigation
