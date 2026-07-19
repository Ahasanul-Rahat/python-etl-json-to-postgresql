# python-etl-json-to-postgresql
# Python ETL Pipeline: JSON to PostgreSQL

## Project Overview

This project demonstrates a complete ETL (Extract, Transform, Load) pipeline using Python.

The pipeline extracts customer transaction data from a JSON file, performs data cleaning and transformation using Pandas, validates data quality, and loads the cleaned data into PostgreSQL using batch insertion.

---

## Technologies

- Python
- Pandas
- PostgreSQL
- Psycopg2
- JSON
- Jupyter Notebook

---

## ETL Workflow

JSON File
↓
Extract
↓
Pandas DataFrame
↓
Data Cleaning
↓
Validation
↓
PostgreSQL

---

## Features

- Read JSON files
- Clean customer names
- Normalize email addresses
- Convert currency values
- Convert dates
- Validate missing values
- Detect duplicate customer IDs
- Create PostgreSQL table automatically
- Bulk insert using execute_batch()
- Handle duplicate primary keys using ON CONFLICT

---

## Libraries

- pandas
- psycopg2
- json

---

## Future Improvements

- REST API Integration
- Logging
- Environment Variables (.env)
- Docker
- Apache Airflow
- Automated Scheduling

---

## Output

Successfully inserted customer transaction records into PostgreSQL.
