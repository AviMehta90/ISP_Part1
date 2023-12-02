# ISP Part 1 - Database Management System Project

## Overview
This repository contains a Python script for managing a PostgreSQL database related to a fictional business scenario. The database includes tables for suppliers, warehouses, products, orders, order details, shipments, and inventory levels.

## Project Structure
- **`main.py`**: Python script for database creation, schema execution, data insertion, and data retrieval.
- **`schema.sql`**: SQL script defining the database schema, including table structures and relationships.
- **`insert_data.sql`**: SQL script containing sample data for insertion into the database.
- **`README.md`**: Project documentation and instructions.

## Requirements
- Python 3.x
- PostgreSQL
- psycopg2 library (install using `pip install psycopg2`)

## Instructions

### 1. Database Creation
- Run the `main.py` script to create a new PostgreSQL database named "mykeyspace" with the specified tables.

```bash
python main.py
```

### 2. Schema Execution
- The script reads the `schema.sql` file and executes it to create the necessary tables and relationships in the database.

### 3. Data Insertion
- The script reads the `insert_data.sql` file and inserts sample data into the created tables.

### 4. Data Retrieval
- The script retrieves and prints data from the "Products" and "Warehouses" tables.

### 5. Customize
- Modify the SQL scripts (`schema.sql` and `insert_data.sql`) or Python script (`main.py`) to suit your specific needs.
