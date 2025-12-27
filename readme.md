\# Online Retail Analytics



\## Project Overview

This project analyzes two years of real-world online retail transaction data to understand

customer behavior, revenue trends, product performance, and geographic distribution.

The analysis focuses on deriving actionable business insights using data cleaning,

exploratory data analysis (EDA), statistics, and visualization.



\## Dataset

\- \*\*Name:\*\* Online Retail II Dataset

\- \*\*Period:\*\* December 2009 – December 2011

\- \*\*Description:\*\* Transaction-level data from a UK-based non-store online retail company

&nbsp; selling gift items. The dataset includes both retail customers and wholesalers.



> Note: Raw data files are excluded from this repository. Instructions to obtain the dataset

are provided in the notebook comments.



\## Objectives

\- Analyze revenue trends and seasonality

\- Understand customer purchasing behavior

\- Identify high-value customers and products

\- Explore geographic revenue distribution

\- Provide business-oriented insights based on data



\## Project Structure

online-retail-analytics/

├── notebooks/

│   ├── 01\_data\_cleaning.ipynb

│   └── 02\_eda.ipynb

├── sql/

│   └── analysis\_queries.sql

├── dashboard/

│   └── (optional visual dashboards)

├── data/

│   └── processed/

├── .gitignore

└── README.md





\## Data Cleaning Summary

\- Standardized column names and data types

\- Removed invalid transactions and returns (negative quantities)

\- Excluded records without customer identifiers for customer-level analysis

\- Retained high-value transactions to preserve wholesaler behavior

\- Created derived revenue metric for analysis



\## Key Insights

\- Revenue shows strong seasonal patterns with consistent peaks during Q4, driven by festive demand.

\- Customer revenue follows a highly skewed long-tailed distribution, where a small fraction of customers contributes a large share of total revenue.

\- Revenue-based segmentation reveals distinct low, medium, and high-value customer groups.

\- A small set of top customers (likely wholesalers) generates disproportionately high revenue, indicating revenue concentration risk.

\- Product sales follow a Pareto distribution, with a few products driving most of the revenue.

\- The United Kingdom dominates revenue contribution, while international markets offer growth potential.

\- Large order sizes confirm the presence of wholesale buyers, justifying the retention of high-value outliers.



\## Tools \& Technologies

\- Python (Pandas, NumPy)

\- Jupyter Notebook

\- Plotly \& Matplotlib for visualization

\- SQL for analytical queries



\## Business Implications

\- Inventory and marketing efforts should be scaled ahead of peak seasonal demand.

\- High-value customers require targeted retention and relationship management.

\- Best-selling products should be prioritized in inventory planning.

\- International markets present opportunities for controlled expansion.



\## Author

Lakshmi Mounika  

M.Tech – Data Science





