# RestauranteDB

This repository contains the SQL scripts and documentation for the RestauranteDB database, which includes the structure and sample data for a restaurant management system.

## Structure

- `sql/` contains SQL scripts for creating tables, inserting data, and running queries.
- `docs/` contains documentation related to the database schema.

## Files

- `create_tables.sql`: SQL script to create the database and tables.
- `insert_data.sql`: SQL script to insert sample data into the tables.
- `queries.sql`: SQL script for sample queries to retrieve data.
- `updates_deletes.sql`: SQL script for updating and deleting data.

## Usage

1. Create the database and tables:
   ```sh
   mysql -u username -p < sql/create_tables.sql
