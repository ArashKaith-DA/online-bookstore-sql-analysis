# Online Bookstore SQL Analysis

## Project Overview

This project uses PostgreSQL to explore and analyze data from an online bookstore. It contains three related datasets: Books, Customers, and Orders.

The project demonstrates how SQL can be used to retrieve information, analyze sales, examine customer purchasing behavior, and summarize business performance.

## Tools Used

- PostgreSQL
- SQL
- CSV datasets
- GitHub

## Database Tables

- **Books:** Book titles, authors, genres, publication years, prices, and stock.
- **Customers:** Customer names, contact details, cities, and countries.
- **Orders:** Customer orders, book IDs, order dates, quantities, and total amounts.

## SQL Concepts Practiced

- SELECT, WHERE, and DISTINCT
- ORDER BY and LIMIT
- Aggregate functions: SUM, AVG, and COUNT
- GROUP BY and HAVING
- INNER JOIN and LEFT JOIN
- Filtering records by dates and numeric conditions
- Revenue and customer spending analysis
- Book sales by genre and author
- Stock remaining calculations

## Business Questions Explored

1. Which books belong to a particular genre?
2. Which books have the highest prices or lowest stock?
3. What is the total stock and revenue recorded in the datasets?
4. How many books were sold by genre and author?
5. Which customers placed multiple orders?
6. Which book was ordered most frequently?
7. Which customers spent the most?
8. How much stock remains after accounting for recorded orders?

## Repository Structure

- `Books.csv` — Book dataset
- `Customers.csv` — Customer dataset
- `Orders.csv` — Order dataset
- `SQL.sql` — Table creation, data import commands, and analysis queries

## How to Run

1. Install PostgreSQL and open a SQL client such as pgAdmin.
2. Create a database for the project.
3. Create the tables using the SQL script.
4. Import the CSV datasets into their corresponding tables.
5. Run the queries to explore the data.

**Note:** Update the CSV file paths in the import commands to match your local environment. The original script uses local Windows file paths.

## Project Goal

The goal of this project is to strengthen practical SQL skills and demonstrate how relational data can be used to answer business questions relevant to data analysis.

