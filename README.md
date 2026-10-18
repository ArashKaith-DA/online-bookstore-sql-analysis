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

## Key Findings

- Generated total recorded revenue of 75,628.66 across 500 orders.
- Recorded 2,697 books ordered, with an average order value of 151.26.
- Romance generated the highest revenue among the seven genres, at 13,086.98.
- Mystery had the highest total quantity sold, with 504 units.
- Identified the highest-spending customer by aggregating order values.
- Identified a book with zero recorded stock, highlighting a potential inventory issue.
- Found 139 customers who placed at least two orders.

## Business Recommendations

- **Genre performance:** Review the pricing, availability, and demand for Romance and Mystery books.
- **Inventory management:** Investigate books with zero stock and determine whether replenishment is needed.
- **Customer retention:** Analyze repeat customers to identify purchasing patterns and opportunities for retention.
- **Sales analysis:** Compare revenue, order quantities, and average order values across genres.

## Limitations

The findings reflect the supplied datasets and do not establish actual business performance. Currency is unspecified, and stock calculations depend on how the Stock field is defined. Customer information should be anonymized before public distribution.

## How to Run

1. Install PostgreSQL and open a SQL client such as pgAdmin.
2. Create a database for the project.
3. Create the tables using the SQL script.
4. Import the CSV datasets into their corresponding tables.
5. Run the queries to explore the data.

**Note:** Update the CSV file paths in the import commands to match your local environment. The original script uses local Windows file paths.

## Project Goal

The goal of this project is to strengthen practical SQL skills and demonstrate how relational data can be used to answer business questions relevant to data analysis.

