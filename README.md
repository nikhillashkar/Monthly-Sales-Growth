# Monthly-Sales-Growth
data analytics project showcasing growth of monthly sales analysis using python, sql and power bi.
# Data Analytics Project

## Overview

This project demonstrates an end-to-end data analytics workflow, covering data extraction, cleaning, exploration, SQL analysis, and dashboard creation. The objective is to transform raw data into actionable insights using Python, PostgreSQL, and Power BI.

The project includes:

* Loading and exploring the dataset using Python
* Performing Exploratory Data Analysis (EDA)
* Cleaning and preprocessing data
* Running SQL queries in PostgreSQL
* Creating interactive dashboards in Power BI
* Generating business insights and recommendations

---

## Dataset

The dataset contains structured data used for analysis and reporting.

**Key Information:**

* Source: [Excel Source]
* Format: CSV / Excel
* Records: [Rows of 520]
* Features: [Columns of 7]

### Sample Columns

* Customer ID
* Product Category
* Sales Amount
* Order Date
* Region

---

## Tools & Technologies

| Tool                 | Purpose                              |
| -------------------- | ------------------------------------ |
| Python               | Data loading, cleaning, and analysis |
| Pandas               | Data manipulation                    |
| NumPy                | Numerical operations                 |
| Matplotlib / Seaborn | Data visualization                   |
| PostgreSQL           | SQL querying and data analysis       |
| Power BI             | Dashboard development                |
| Jupyter Notebook     | Analysis environment                 |

---

## Project Workflow

### 1. Data Loading

* Imported dataset into Python using Pandas.
* Inspected data structure and data types.
* Identified missing and duplicate records.

### 2. Exploratory Data Analysis (EDA)

* Analyzed data distributions.
* Examined trends and patterns.
* Generated summary statistics.
* Created visualizations to identify insights.

### 3. Data Cleaning

* Handled missing values.
* Removed duplicates.
* Corrected inconsistent data formats.
* Prepared data for analysis and reporting.

### 4. SQL Analysis (PostgreSQL)

* Imported cleaned data into PostgreSQL.
  
**Example Analyses:**

* Top-performing products
* Regional sales performance
* Monthly sales trends
* Customer behavior insights

### 5. Power BI Dashboard

* Connected Power BI to processed data.
* Built interactive visualizations.
* Added filters and slicers for dynamic reporting.
* Created KPI cards and trend charts.

---

## Dashboard Features

The Power BI dashboard includes:

* Sales Overview
* Revenue Trends
* Regional Performance Analysis
* Product Category Insights
* Key Performance Indicators (KPIs)
* Interactive Filters and Slicers

---

## Results & Insights

Key findings from the analysis include:

* Identification of top-performing products and regions.
* Discovery of sales trends over time.
* Insights into customer purchasing behavior.
* Data-driven recommendations for business decision-making.

---

## Project Structure

```text
Data-Analytics-Project/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── eda_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
├── images/
│   └── dashboard_screenshot.png
│
└── README.md
```

---

## How to Run

### Prerequisites

* Python 3.x
* PostgreSQL
* Power BI Desktop

### Steps

1. Clone the repository:

```bash
git clone https://github.com/yourusername/project-name.git
```

2. Install required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn psycopg2
```

3. Open and run the Jupyter Notebook for EDA and data cleaning.

4. Import the cleaned dataset into PostgreSQL.

5. Execute SQL queries from:

```text
sql/analysis_queries.sql
```

6. Open the Power BI dashboard file:

```text
dashboard/powerbi_dashboard.pbix
```

7. Refresh the data connection to view updated insights.

---

## Future Improvements

* Automate data pipeline using ETL processes.
* Add advanced statistical analysis.
* Integrate real-time data sources.
* Deploy dashboards to Power BI Service.

---

## Author

**[Nikhil Lashkar]**

Data Analytics Project showcasing Python, SQL, PostgreSQL, and Power BI skills for data-driven decision making.
