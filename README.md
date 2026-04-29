# Spark ETL Pipeline – US City Population & Housing Analysis

## Overview
An ETL pipeline built with Apache Spark on Databricks that processes US city population and housing price data.

## Pipeline Steps
1. **Extract** – Loaded raw CSV data into a Spark DataFrame
2. **Transform** – Cleaned null values, renamed columns, filtered large cities (population > 500,000)
3. **Aggregate** – Calculated average median house prices grouped by state
4. **Export** – Converted final results to Pandas for reporting

## Tools & Technologies
- Apache Spark 4.1.0
- Databricks Community Edition
- PySpark
- Python
- Pandas

## Key Learnings
- Spark DataFrame operations vs Pandas
- PySpark groupBy and aggregation functions
- End-to-end ETL workflow on a cloud platform
