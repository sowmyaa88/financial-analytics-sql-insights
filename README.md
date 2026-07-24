# 📈 Financial Analytics & SQL Insights Engine

> **Enterprise Use Case:** Advanced T-SQL exploratory data analysis (EDA) and analytical query framework designed to transform raw transactional database layers into executive financial KPIs, customer cohort trends, and revenue growth metrics.

---

## 📌 Business & Analytical Overview

In Private Equity (PE) advisory and corporate finance, clean data modeling must be paired with high-performance SQL query engineering to deliver actionable insights. This project demonstrates how to query a Gold-layer database schema to extract core operational and financial metrics required by CFOs and investment sponsors.


### Core Business Objectives Addressed:
* **Revenue & Performance Tracking:** Calculating Month-over-Month (MoM) growth, running totals, and cumulative revenue performance across product lines and business units.
* **Customer Retention & Churn:** Building cohort retention analysis models using SQL Window functions to track customer lifecycle value.
* **RFM Segmentation:** Implementing Recency, Frequency, and Monetary value models to segment portfolio customer bases into actionable tier groups.
* **Product & Order Performance:** Identifying top/bottom performing product portfolios using dynamic ranking and percentile distribution logic.

---

## 🛠️ Advanced SQL Techniques Demonstrated

This project leverages complex T-SQL techniques to solve non-trivial reporting problems without relying on external processing tools:

* **Window Functions:** `SUM() OVER()`, `LAG()`, `LEAD()`, `ROW_NUMBER()`, `DENSE_RANK()`, `NTILE()`
* **Common Table Expressions (CTEs):** Multi-level modularized query structures to isolate complex logic steps.
* **Aggregations & Conditional Logic:** `CASE WHEN` constructs for custom categorizations and pivoted reporting matrices.
* **Date & Time Intelligence:** Advanced date functions (`DATEDIFF`, `DATEADD`, `EOMONTH`) for rolling-period and fiscal-year calculations.

---

## 📂 Repository Structure

```text

scripts/
├── 00_init_database.sql          # Database initialization & schema setup
├── 01_database_exploration.sql   # Data profiling & record-level auditing
├── 02_dimensions_exploration.sql # Dimensional attribute mapping & category counts
├── 03_date_range_exploration.sql # Time-series boundaries & period coverage
├── 04_measures_exploration.sql   # Core quantitative metrics & aggregate checks
├── 05_magnitude_analysis.sql     # Volume, size, and distribution metrics
├── 06_ranking_analysis.sql       # Top/Bottom performance benchmarking
├── 07_change_over_time_analysis.sql # Period-over-Period & MoM growth trends
├── 08_cumulative_analysis.sql    # Running totals & cumulative financial metrics
├── 09_performance_analysis.sql   # Operational targets vs. actual performance
├── 10_data_segmentation.sql      # RFM modeling & customer group profiling
├── 11_part_to_whole_analysis.sql # Share of total, Pareto, & ratio analyses
├── 12_report_customers.sql       # Gold-layer views for customer reporting
└── 13_report_products.sql        # Gold-layer views for product reporting
```

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

