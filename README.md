# Task 6 – Sales Trend Analysis Using SQL

##  Objective
Analyze monthly revenue and number of orders using SQL aggregation.

##  Tools Used
- SQL Engine: SQLite
- Platform: [sqliteonline.com](https://sqliteonline.com)

##  What I Did
1. Created a table `online_sales` with columns for order ID, date, amount, and product.
2. Inserted 6 rows of sample data simulating e-commerce transactions.
3. Wrote an SQL query to:
   - Extract month and year from order_date
   - Calculate monthly revenue using `SUM(amount)`
   - Calculate order volume using `COUNT(DISTINCT order_id)`
   - Sort results in descending order of revenue

##  Output (Sales Trend)

| Year | Month | Revenue | Total Orders |
|------|-------|---------|--------------|
| 2024 | 03    | 6000    | 3            |
| 2024 | 01    | 3500    | 2            |
| 2024 | 02    | 1000    | 1            |

Screenshot below shows the query output:

![Sales Trend Output](screenshot.png)

## Learning Outcomes
- Used `GROUP BY`, `ORDER BY`, `SUM()`, and `COUNT()` functions
- Practiced data aggregation and time-based analysis in SQL
# TASK6-SALES-TREND
