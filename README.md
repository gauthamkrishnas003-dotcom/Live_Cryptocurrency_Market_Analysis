# Live Cryptocurrency Market Analysis

A Python-based Exploratory Data Analysis (EDA) project that retrieves cryptocurrency market data from Yahoo Finance and explores price movements, trading volume, returns, volatility, and relationships between selected cryptocurrencies.

## Project Overview

This project uses the `yfinance` library to retrieve cryptocurrency market data. The data is processed with Pandas and NumPy and visualized using Matplotlib and Seaborn.

The default cryptocurrencies used in the project are:

- Bitcoin (`BTC-USD`)
- Ethereum (`ETH-USD`)
- BNB (`BNB-USD`)
- XRP (`XRP-USD`)
- Dogecoin (`DOGE-USD`)

You can change or add ticker symbols in the notebook or Python script.

> **Note:** This project fetches market data when the code is run. It is not a guaranteed real-time trading feed. Data availability and update frequency depend on Yahoo Finance.

## Objectives

- Retrieve cryptocurrency market data from Yahoo Finance.
- Compare historical prices across selected cryptocurrencies.
- Examine daily percentage returns and trading volumes.
- Explore volatility and correlations.
- Present findings through data visualizations.

## Technologies Used

- Python
- Pandas
- NumPy
- yfinance
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
Live_Cryptocurrency_Market_Analysis/
│
├── data/                 # Optional: downloaded datasets
├── notebooks/            # Jupyter notebooks
├── outputs/              # Saved charts and analysis results
├── README.md
└── requirements.txt
```

Your actual folder structure may differ. Update this section if you organize the project differently.

## Installation and Setup

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd Live_Cryptocurrency_Market_Analysis
```

### 2. Create and activate a virtual environment (optional)

```bash
python -m venv .venv
```

On Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the project

Open the notebook in Jupyter Notebook, JupyterLab, or PyCharm and run the cells in order.

If you use a Python script instead, run:

```bash
python your_script_name.py
```

## Example Analysis

Depending on the analysis implemented in the notebook, the project can include:

- Historical closing-price comparison
- Daily returns
- Trading-volume trends
- Volatility comparison
- Correlation heatmap

## Data Source

Market data is retrieved from [Yahoo Finance](https://finance.yahoo.com/).

## Disclaimer

This project is intended for educational and analytical purposes only. It does not provide financial advice or trading recommendations. Cryptocurrency prices are volatile, and data may be delayed, incomplete, or revised by the data provider.

## Author

**Gauthamkrishna S**
