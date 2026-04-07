# Databricks Learning Projects

## About
PySpark and Delta Lake projects built during my
Databricks learning journey.

## Projects

### Week 1 — Retail Sales Pipeline
End-to-end Bronze → Silver → Gold pipeline
analyzing retail sales data across cities and categories.

**Tech stack:** PySpark · Delta Lake · Databricks SQL

**What it does:**
- Ingests raw sales data into a Bronze Delta table
- Cleans and standardizes data in Silver layer
  (nulls, inconsistent city names, calculated columns)
- Produces Gold summary tables by city and category
- Answers 5 business questions using SQL

**Tables created:**
- retail_bronze — raw ingested data
- retail_silver — cleaned and transformed
- retail_gold_by_city — revenue summary by city
- retail_gold_by_category — revenue summary by category
