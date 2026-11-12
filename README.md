# Medallion Architecture Using PySpark and DuckDB

## Project Overview

This project demonstrates the implementation of Medallion Architecture using PySpark and DuckDB.

The objective is to build a structured data processing pipeline by organizing data into three layers: Bronze, Silver, and Gold.

PySpark is used for data ingestion and transformation, while DuckDB is used for storing, querying, and analyzing structured data.

## Technology Stack

- **Python** – Programming language
- **PySpark** – Data processing and transformation
- **DuckDB** – Analytical database
- **SQL** – Data querying and analysis
- **Jupyter Notebook** – Development and experimentation
- **Git & GitHub** – Version control and project management

## Project Structure

```text
medallion_project_duckdb/
│
├── data/
│   ├── source/          # Original source data
│   ├── bronze/          # Raw ingested data
│   ├── silver/          # Cleaned and transformed data
│   └── gold/            # Business-ready data
│
├── database/            # Local DuckDB database files
│
├── notebooks/
│   ├── 01_bronze_layer/
│   ├── 02_silver_layer/
│   └── 03_gold_layer/
│
├── .gitignore
└── README.md
```

## Medallion Architecture

### 1. Bronze Layer
- Ingest raw data from source systems.
- Preserve the original data.
- Perform initial data loading.

### 2. Silver Layer
- Clean and validate data.
- Handle missing and duplicate records.
- Apply necessary transformations.
- Maintain data quality.

### 3. Gold Layer
- Perform aggregations and business-level transformations.
- Create analytical datasets.
- Prepare data for reporting and analysis.

## Project Workflow

```text
Source Data
    |
    v
Bronze Layer
    |
    v
Silver Layer
    |
    v
Gold Layer
    |
    v
Analytics and Reporting
```

## Project Goals

- Understand and implement Medallion Architecture.
- Practice PySpark DataFrame transformations.
- Work with DuckDB for analytical SQL queries.
- Build a structured ETL/ELT pipeline.
- Understand data organization across Bronze, Silver, and Gold layers.

## Future Enhancements

- Implement incremental data loading.
- Implement Slowly Changing Dimensions (SCD Type 1 and Type 2).
- Add data quality checks.
- Implement logging and error handling.
- Optimize data processing and analytical queries.

---

**Author:** Deepqa16

**Project:** Medallion Architecture Using PySpark and DuckDB