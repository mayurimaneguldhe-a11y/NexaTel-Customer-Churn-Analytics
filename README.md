# NexaTel Customer Churn Analytics

Python and Power BI analysis of a simulated telecom customer base: data quality checks, exploratory analysis, churn KPIs, a 5-page dashboard and a management report.

**Business question:** Which customers and segments is NexaTel losing, and what separates the customers who stay?

## Key findings

| Metric | Result |
| --- | --- |
| Customers analysed | 19,000 across 24 related tables |
| Overall churn | **18.45%** (3,506 customers) |
| Churn by segment | Mass **26.7%** vs Enterprise **11.9%** (about 2.2x) |
| Churn by product line | Ranges from 6.2% to 23.2% |
| Retention offers | 86.8% of customers who accepted an offer were retained vs 79.2% of those who declined |
| Data quality issues flagged | 172 future-dated invoices, 229 negative billing amounts, plus invalid ages, PIN codes and phone numbers |

## Project phases

| Phase | What I did | File |
| --- | --- | --- |
| 1. Data quality checks | Checked the 24 tables for missing values, duplicates, invalid formats, date logic and referential integrity; flagged issues without altering the source data. | `Phase1_DataCleaning_Mayuri_Maneguldhe.ipynb` |
| 2. Exploratory data analysis | Pandas and Matplotlib analysis of churn by segment, product line, tenure, plan and region. | `Phase2_EDA_Mayuri_Maneguldhe.ipynb` |
| 3. KPI calculation | Churn rate, segment and product-line churn, retention-offer outcomes and revenue KPIs. | `Phase3_KPIs_Mayuri_Maneguldhe.ipynb` |
| 4. Dashboard and report | 5-page Power BI dashboard with 20+ DAX measures and a management report. | `Phase4_Dashboard_Mayuri_Maneguldhe.pbix`, `Phase4_Report_Mayuri_Maneguldhe.docx` |

## Dashboard

Pages: Executive Overview, Customer & Segment, Service & Support, Network & Regional, Campaigns & Revenue.

Open `Phase4_Dashboard_Mayuri_Maneguldhe.pbix` in Power BI Desktop (free), or see `Phase4_Dashboard_Mayuri_Maneguldhe.pdf` for a static export.


## Data

The dataset is simulated: 19,000 customers across 24 tables covering contracts, billing, payments, complaints, support tickets, network quality, retention campaigns and geography. The raw data file is not included in this repository.

## How to run

1. Install the packages: `pip install -r requirements.txt`
2. Run the notebooks in order, Phase 1 to Phase 3.

## Tech stack

Python (pandas, NumPy, Matplotlib) · Power BI (DAX) · Excel · Jupyter Notebook

## Author

Mayuri Maneguldhe · [GitHub](https://github.com/mayurimaneguldhe-a11y) · [LinkedIn](https://www.linkedin.com/in/mayuri-maneguldhe-558621309)
