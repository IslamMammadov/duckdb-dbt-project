# Data Engineering Project with DuckDB & dbt  

## Overview  
This project demonstrates a simple **data engineering pipeline** using **dbt (Data Build Tool)** and **DuckDB**. It processes **New York Violation 2013** sample data, transforming it through a structured data warehouse (DWH) model with **bronze, silver, and gold** layers.  

## Features  
- **Data Transformation**: Uses `dbt` to clean, structure, and transform raw data.  
- **Layered Architecture**: Implements **bronze (raw), silver (cleaned), and gold (aggregated)** layers in a `DuckDB` environment.
- Data Warehouse Layers
  Bronze: Raw ingestion layer with minimal transformation.
  Silver: Cleaned and structured data, with necessary formatting applied.
  Gold: Aggregated data for reporting and analytics.
- **Testing & Documentation**: Runs **basic `dbt` tests** and includes **documentation** for clarity.  

## Project Structure  
```plaintext
duckdb-dbt-project/  
│-- models/                # dbt models (Bronze, Silver, Gold layers)  
│-- tests/                 # dbt tests for data validation  
│-- snapshots/             # Snapshot configuration (if applicable)  
│-- dbt_project.yml        # dbt project settings  
│-- README.md              # Project documentation
data
run_queries.ipynb
```

