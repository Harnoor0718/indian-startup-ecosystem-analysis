# Indian Startup Ecosystem Analysis – Funding & Unicorn Trends

> Data Analytics Major Project | CGC University, Mohali | Data Science Batch-3 | Roll No: 2419864

---

## Project Overview

A comprehensive end-to-end data analytics project analyzing India's startup ecosystem (2015–2023), covering funding trends, sector growth, investor activity, geographic distribution, and unicorn companies.

---

## Key Findings

- **E-Commerce leads** total funding at **$8.2B** — revealed only after fixing duplicate sector names
- **Bengaluru** is India's startup capital with **582 startups** — 1.5x more than Mumbai
- **2021 was the unicorn boom year** — 44 new unicorns created in a single year
- **Series B** has the highest avg deal size at **$240M** — the critical scaling stage
- **CAGR of 3.03%** (2015–2019) masks extreme year-to-year volatility
- **Mean ($18.48M) vs Median ($1.75M)** gap reveals extreme funding inequality

---

## Project Structure
data/raw/              - original downloaded datasets
data/cleaned/          - cleaned, processed master dataset
notebooks/
01_data_loading_and_cleaning.ipynb   - data cleaning pipeline
02_eda_funding_trends.ipynb          - EDA and visualizations
03_unicorn_analysis.ipynb            - unicorn + SQL analysis
reports/               - PDF report, PPT, exported charts
dashboard/             - Power BI .pbix file + screenshot

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy) | Data cleaning and analysis |
| Matplotlib, Seaborn | EDA visualizations (10+ charts) |
| SQLite (sqlite3) | SQL business queries |
| Power BI | Interactive dashboard |
| Jupyter Notebook | Development environment |
| Git + GitHub | Version control (25+ commits) |

---

## Datasets

| Dataset | Source | Records |
|---------|--------|---------|
| Indian Startup Funding | Kaggle (SRK) | 3,044 rows |
| Indian Unicorn Startups | Kaggle | 102 rows |

---

## Deliverables

- Jupyter Notebooks (3)
- 10+ EDA charts saved as PNG
- Power BI interactive dashboard
- 10-page written report (PDF)
- 15-slide PowerPoint presentation
- GitHub repo with 25+ commits

---

## Statistical Summary

| Metric | Value |
|--------|-------|
| Total Funding | $38.05 Billion |
| Total Deals | 2,059 |
| Mean Deal Size | $18.48M |
| Median Deal Size | $1.75M |
| Total Unicorns | 102 |
| Peak Unicorn Year | 2021 (44 unicorns) |
| CAGR (2015–2019) | 3.03% |