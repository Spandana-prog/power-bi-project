# 📊Sales Performance Dashboard

## 🔎Project Overview

This project is an **interactive Sales Performance Dashboard** built in **Power BI.**
The goal was to transform raw sales data into clear, actionable insights, allowing users to:

- Track sales trends

- Measure sales agent performance

- Monitor the overall health of the sales pipeline

## 🛠Skills Demonstrated

- Data Cleaning: Cleaned and transformed raw CSV data using Power Query.

- Data Modeling: Built a star schema model to efficiently connect multiple tables.

- DAX Formulas: Created custom measures for KPIs and advanced calculations.

- Dashboard Design: Designed an intuitive and visually appealing dashboard.

- Data Storytelling: Structured visuals to communicate business insights effectively.

## 📈Key Performance Indicators (KPIs) & Visuals

- Sales Funnel: Funnel chart showing deal conversion from Lead → Won.

- Sales Cycle Length: Average days taken by each sales agent to close a deal.

- Win Rate: Percentage of opportunities successfully closed as sales.

- Total Sales by Sector: Bar chart comparing closed sales across industries.

- Sales by Quarter & Month: Line chart to identify seasonal trends and growth.


## 📂 Data Model

The dashboard is built on a star schema for optimal performance and analytics.

### Fact Table:

- sales_pipeline → Contains transaction-level sales data

### Dimension Tables:

- accounts → Customer details (industry, sector, etc.)

- sales_teams → Sales agents and managers

### Relationships:

- One-to-many: sales_teams → sales_pipeline

- One-to-many: accounts → sales_pipeline

## 💻 Tech Stack

- Power BI (Data Visualization)

- Power Query (ETL / Data Cleaning)

- DAX (Business Logic & Calculations)

- Star Schema Data Modeling

- CSV Data Source (from Iqra Technology)

## 📷 Dashboard Preview

![Dashboard Image](/project%20pic%2022.png)

### Data Source: Sales dataset from Maven Analytics (cleaned & transformed for analysis).


## Conclusion

The Dashboard showcases how Power Bi can transform raw sales data into a powerful toll for sales pipeline analysis.