# Fin_Bal_Pyt

Financial statement analysis notebooks in Python, from May 2021.

## What it is

A set of Jupyter notebooks that pull balance sheet data via the [Financial Modeling Prep](https://financialmodelingprep.com/) API (for one company and for multiple companies) and analyze it: accounts receivable, inventory, liquidity, and solvency, plus a notebook on "common size" balance sheets and one using Plotly for visualization. Written by the author while at NITK, per the original README's attribution.

## Stack

- Python, Jupyter notebooks
- `requests` + the Financial Modeling Prep API for data
- pandas for analysis, Plotly for charts

## Running it

Each notebook needs a Financial Modeling Prep API key. **`Fin_python_single_company.ipynb` has a real-looking API key hardcoded in the first cell** — worth rotating/revoking if it's still live, and removing before treating this repo as a portfolio sample. Not executed as part of this review.

## Status

Written in May 2021 as a set of financial-analysis exercises. Not maintained.
