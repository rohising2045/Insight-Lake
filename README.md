# Insight Lake (Retail Data Engineering & Analytics Using Databricks)

📌 Project Overview

This project focuses on building a retail data processing and analytics pipeline using **Databricks, Apache Spark (PySpark), SQL, and Power BI**. The objective is to transform raw retail data into structured datasets and generate meaningful business insights through data analysis and visualization.

The project uses a synthetic retail dataset containing customers, orders, products, and regions.

🏗️ Medallion Architecture

This project implements the Medallion Architecture in Databricks to organize and process retail data through structured data layers.

🥉 Bronze Layer:** Ingested raw retail datasets, including customers, orders, products, and regions, into Databricks tables.
🥈 Silver Layer:** Processed and transformed data to prepare reliable datasets for downstream analytics.
🥇 Gold Layer:** Created business-ready analytical datasets, including monthly sales summaries and profit analysis.
📊 Power BI Integration:** Connected analytical datasets to Power BI to build interactive dashboards and visualize key business metrics.

This layered approach improves data organization, maintainability, and the usability of data for business intelligence and reporting.

🎯 Project Objectives

- Process large volumes of retail data using PySpark.
- Organize data into structured tables for analytics.
- Perform data transformations and aggregations using Spark SQL.
- Analyze sales, revenue, costs, and profit.
- Prepare analytical datasets for Power BI dashboards.
- Develop practical skills relevant to Data Engineering.

🛠️ Technologies Used

- **Databricks Free Edition** — Data processing environment
- **Apache Spark / PySpark** — Distributed data processing
- **Spark SQL** — Data querying and aggregation
- **Delta Lake** — Table storage and management, where applicable
- **Power BI** — Data visualization and business reporting
- **CSV** — Source data format

📂 Dataset Description

The project uses four synthetic datasets:

| Dataset | Number of Records |
|---|---:|
| Customers | 150,000 |
| Orders | 250,000 |
| Products | 500 |
| Regions | 4 |

The datasets contain information about customers, transactions, products, and geographical regions.

⚙️ Project Workflow

1. **Data Ingestion:** Uploaded CSV files into Databricks.
2. **Data Loading:** Loaded the datasets into Spark DataFrames.
3. **Bronze Layer:** Created bronze tables for customers, orders, products, and regions.
4. **Data Processing:** Used PySpark and SQL to query, transform, and aggregate retail data.
5. **Gold-Level Analytics:** Created analytical outputs, including monthly sales and profit analysis.
6. **Power BI Integration:** Connected the analytical data to Power BI for business reporting.
7. **Dashboard Development:** Built KPI cards and charts to analyze revenue, profit, costs, and product performance.

📊 Key Business Metrics

- Total Revenue
- Total Cost
- Total Profit
- Monthly Sales Trends
- Product-wise Revenue and Profit
- Regional Sales Performance

 📊 Power BI Dashboard's

![Power BI Dashboard](<Screenshots/Screenshot 2026-10-21 054539.png>)

![Power BI Dashboard](<Screenshots/MixCollage-21-Oct-2026-06-48-AM-7235.jpg>)


💡 Key Learnings

- Working with large datasets in Databricks.
- Loading and processing CSV files using PySpark.
- Creating and querying Spark tables.
- Performing aggregations using SQL.
- Preparing data for business intelligence reporting.
- Connecting Databricks analytical data with Power BI.

🚀 Future Enhancements

- Add data quality checks and duplicate handling.
- Implement incremental data processing.
- Optimize queries and data storage.
- Automate pipeline execution.
- Add more advanced business KPIs and dashboard filters.

👨‍💻 Author

**Rohit Singh**

Database Analyst | SQL | Python | PySpark | Databricks | Azure Data Factory | Power BI
