# Emissions Dashboard — Databricks Visualization Project

## Overview
This project was created to learn **data visualization using Databricks SQL and Databricks Dashboards**.  
Using a 2023 U.S. emissions dataset, I explored how to clean raw CSV data, write analytical SQL queries, and build interactive visualizations directly within Databricks.

---

## Dataset
- `Emissions_Data_2023.csv`
- U.S. county- and state-level data
- Key fields: county/state, population, GHG emissions (CO₂e)

---

## What I Learned
- Loading CSV data into Databricks
- Cleaning numeric fields using SQL (`CAST`, `REGEXP_REPLACE`)
- Using CTEs (`WITH` clauses) instead of views for analysis
- Creating bar charts, scatter plots, and maps in Databricks
- Building an interactive dashboard with filters and linked visuals

---

## Visualizations Built
- **Top states by total emissions**
- **County-level emissions per person**
- **Scatter plots** to compare:
  - Population vs total emissions
  - Total emissions vs emissions per person
- **Geographic map** showing emissions distribution

---

## Tools Used
- Databricks SQL
- Databricks Dashboards
- SQL (CTEs, aggregations, calculations)

---

## Key Insight
Total emissions and per-capita emissions tell different stories—scatter plots helped identify counties where emissions intensity is high despite smaller populations.

---

## Author
**Samyuktha Sampath**  
MS in Business Analytics, University of Colorado Boulder
