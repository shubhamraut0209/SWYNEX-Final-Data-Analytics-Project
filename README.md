# E-Commerce Retail Analytics — Final Case Study

**SWYNEX Technologies Data Analyst Internship | Task 4**  
**Author:** Shubham Umesh Raut

An end-to-end analytics case study combining data preparation, exploratory data analysis, an interactive dashboard, and business recommendations using an e-commerce retail transactions dataset.

## Project at a glance

- **Dataset size:** 11,814 records × 16 original columns
- **Date range:** 2024-01-01 to 2026-06-30
- **Estimated gross sales:** $1,500,541.86
- **Estimated discounts:** $102,514.78
- **Estimated net sales:** $1,398,027.08
- **Tools:** Python, Pandas, NumPy, Matplotlib, HTML, CSS, JavaScript

> Sales metrics are estimates based on quantity, unit price, and discount percentage. They should not be interpreted as audited revenue.

## Start here

1. Read [`FINAL_ANALYTICS_CASE_STUDY.md`](FINAL_ANALYTICS_CASE_STUDY.md) for the complete case study.
2. Open [`dashboard/SWYNEX_Ecommerce_Interactive_Dashboard.html`](dashboard/SWYNEX_Ecommerce_Interactive_Dashboard.html) in a modern browser for the interactive dashboard.
3. Review [`analysis/SWYNEX_Task_2_EDA.ipynb`](analysis/SWYNEX_Task_2_EDA.ipynb) for the EDA notebook.
4. Explore charts and summary CSVs under `analysis/`.

## Case study workflow

1. **Data preparation:** inspect the cleaned dataset, data types, duplicate records, and missing values.
2. **Exploratory analysis:** calculate descriptive statistics and estimated sales metrics.
3. **Visualization:** compare category and monthly sales, payment methods, order statuses, ratings, and countries.
4. **Dashboarding:** explore KPIs and charts with date, category, country, and payment-method filters.
5. **Business interpretation:** document findings, limitations, and follow-up recommendations.

## Key findings

- **Electronics** is the largest category by estimated net sales, contributing 27.0%.
- **United Arab Emirates** leads estimated net sales by country, contributing 15.1%.
- **Cash on Delivery** is the most frequently recorded payment method, at 17.3% of transaction records.
- The mean customer rating is 3.90/5 among records with ratings, but 50.5% of records have no rating.

## Repository structure

```text
SWYNEX-Task-4-Final-Analytics-Case-Study/
├── README.md
├── FINAL_ANALYTICS_CASE_STUDY.md
├── data/
│   └── ecommerce_retail_transactions_cleaned.csv
├── dashboard/
│   └── SWYNEX_Ecommerce_Interactive_Dashboard.html
└── analysis/
    ├── SWYNEX_Task_2_EDA.ipynb
    ├── charts/
    └── summaries/
```

## Run the analysis

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Open the notebook in Jupyter Notebook or Google Colab. If using a local Jupyter session, ensure the dataset path matches the file location in the notebook. The dashboard is a standalone HTML file and can be opened directly in a browser.

## Important limitations

- The supplied files do not identify the dataset's external source or provide a full data dictionary.
- Sales values are estimates; tax, shipping, returns, refunds, and other adjustments are not independently accounted for.
- Missing ratings and city fields limit some analysis.
- Order-status counts do not establish delivery success rates without event history.
- Descriptive patterns do not prove causation.

## Author

**Shubham Umesh Raut**  
M.Sc. Statistics | B.Sc. Mathematics  
[LinkedIn](https://www.linkedin.com/in/shubham-raut-986bb1227/)

*Created as the final analytics case study for the SWYNEX Technologies Data Analyst Internship.*
