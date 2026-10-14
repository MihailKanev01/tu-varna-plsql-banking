# Banking Database — PL/SQL

A relational database exercise modelling banking data with Oracle SQL scripts.

## Overview

The repository is organised as a sequential set of scripts for creating database tables, inserting sample records, and demonstrating updates and deletes.

## Scripts

| File | Purpose |
| --- | --- |
| `01_create_tables.sql` | Create the database schema |
| `02_insert_data.sql` | Insert sample data |
| `03_updates_and_deletes.sql` | Demonstrate data modification statements |

## What It Demonstrates

- Relational schema design
- Data definition language (DDL)
- Data manipulation language (DML)
- Executing scripts in a controlled order

## Run Locally

**Requirements:** An Oracle-compatible SQL environment, such as Oracle Database with SQL Developer.

1. Open your SQL client and connect to a development or test schema.
2. Run `01_create_tables.sql`.
3. Run `02_insert_data.sql`.
4. Run `03_updates_and_deletes.sql` after reviewing the statements.

> Run these scripts only in a test schema. The update and delete examples modify data.

## Project Status

An educational database project focused on SQL schema creation and data manipulation, not a production banking system.
