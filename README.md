# Data-Acquisition-and-Visualization-of-TSLA-GME-A-Price-Revenue-Study
# Tesla & GameStop: Price–Revenue Dashboard (yfinance + web scraping)

This project acquires historical close prices for Tesla (TSLA) and GameStop (GME) using yfinance, scrapes quarterly revenue tables from Macrotrends with pandas.read_html, and cleans/aligns the data. It then visualizes each company with a simple dashboard: price (line) overlaid with revenue (bars) on dual y-axes. The notebook is fully reproducible and includes screenshots for the Coursera submission. Stack: Python, pandas, yfinance, Plotly, lxml/BeautifulSoup.

## What’s inside
- `Price-revenue_dashboard.ipynb` — pulls TSLA & GME price data with `yfinance`, scrapes quarterly revenue from Macrotrends, and builds two dashboards (price vs revenue).

## How to run
```bash
pip install -r requirements.txt
# open the notebook in Jupyter or VS Code
