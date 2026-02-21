# customer-trends-data-analysis-SQL-Python-PowerBI
# Data Analytics Project

## Overview

This project demonstrates an end‑to‑end data analytics workflow: loading and processing data in Python, performing exploratory data analysis (EDA) and cleaning, querying data in PostgreSQL, and building an interactive Power BI dashboard. Insights are summarized in a written report and presentation (Gamma PPT). The goal is to extract actionable insights and present them clearly for business decision‑making.

## Datasets

* Source: [[customer_shopping_behavior.csv](https://github.com/user-attachments/files/25460562/customer_shopping_behavior.csv)
]
* Format: CSV/Excel/Database export
* Size: [Rows × Columns]
* Key fields: [e.g., date, category, sales, customer_id]

## Tools & Technologies

* **Python:** pandas, numpy, matplotlib, seaborn
* **SQL:** PostgreSQL
* **Visualization:** Power BI
* **Reporting:** MS Word / PDF
* **Presentation:** Gamma
* **Environment:** Jupyter Notebook / VS Code

## Project Steps

1. **Data Loading (Python)**

   * Imported raw datasets into pandas DataFrames.
   * Validated schema and basic structure.

2. **Exploratory Data Analysis (EDA)**

   * Checked distributions, trends, correlations.
   * Identified missing values and outliers.
   * Created summary statistics and plots.

3. **Data Cleaning & Preparation**

   * Handled missing values and duplicates.
   * Standardized formats (dates, categories, text).
   * Created derived features for analysis.

4. **SQL Analysis (PostgreSQL)**

   * Loaded cleaned data into PostgreSQL tables.
   * Wrote analytical queries (aggregations, joins, filters).
   * Generated business metrics and views for BI.

5. **Dashboard Development (Power BI)**

   * Connected Power BI to PostgreSQL / processed data.
   * Built interactive visuals (KPIs, trends, category analysis).
   * Added slicers and filters for user exploration.

6. **Reporting & Presentation**

   * Documented methodology and insights in a report.
   * Created presentation slides using Gamma.

## Dashboard

* KPIs: [e.g., total sales, growth rate, top categories]
* Visuals: trend charts, category comparisons, geographic view
* Interactivity: filters by time, category, region
* File: `dashboard.pbix`

## Results & Insights

* Identified key trends and patterns in the dataset.
* Highlighted top‑performing segments and anomalies.
* Provided data‑driven recommendations.
* Delivered insights through dashboard and report.

## How to Run

1. **Clone repository**

   ```bash
   git clone <repo_url>
   cd <project_folder>
   ```

2. **Set up environment**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run Python analysis**

   * Open ``
   * Execute all cells to reproduce EDA and cleaning.

4. **Load data into PostgreSQL**

   * Create database and tables.
   * Run SQL scripts in `sql/` folder.

5. **Open Power BI dashboard**

   * Open `` in Power BI Desktop.
   * Refresh data source if needed.

## Repository Structure

```
project/
│
├─ data/                # Raw and cleaned datasets
├─ notebooks/           # Python EDA & cleaning
├─ sql/                 # SQL queries and schema
├─ dashboard/           # Power BI file (.pbix)
├─ report/              # Final report (PDF/Doc)
├─ presentation/        # Gamma PPT export
├─ requirements.txt     # Python dependencies
└─ README.md
```

## Author

**Mayank Gupta**
Email: [mayankguptag055@gmail.com](mailto:mayankguptag055@gmail.com)


---

*This project showcases practical skills in Python, SQL, and BI tools for real‑world data analytics workflows.*
