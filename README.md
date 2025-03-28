# DuckDB and dbt Data Transformation Project

This project demonstrates a simple data engineering workflow using **DuckDB** and **dbt** to transform New York City parking violation data from 2013. The data is processed in three layers (bronze, silver, gold) with basic tests and documentation.

## Project Overview

- **Source Data**: Sample NYC Parking Violations (2013)
- **Tools Used**:
  - DuckDB (in-memory analytical database)
  - dbt (data transformation)
- **Layers**:
  - **Bronze**: Raw data ingestion
  - **Silver**: Cleaned and standardized data
  - **Gold**: Business-ready aggregates and final tables

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/IslamMammadov/duckdb-dbt-project.git
   cd duckdb-dbt-project
   ```
