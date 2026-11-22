## Sql-Witle-Academy-Class-Exercise
SQL Class Exercise. Selecting and Filtering. Aggregation. Joins. Subqueries and CTEs. Window Functions

## 20 Questions

# Table of Contents
## Part A - Selecting and Filtering
## Part B - Aggregation
## Part C - Joins
## Part D - Subqueries and CTEs
## Part E - Window Functions

## Data sets 

Data Sets/
├── customers.csv
├── products.csv
├── sales_orders.csv
├── sales_lines.csv
├── ar_ledger.csv
├── reps.csv
├── rep_visits.csv
├── trade_promotions.csv
└── vendors.csv
## Part A - Selecting and Filtering

Question 1 - Every product on the price list 
Nomsa in Finance wants the current price list. Return the SKU, product name, product line and list price 
for every product, sorted by product line and then by price. 
Answer 1 - Every product on the price list 
Select*

Question 2 - One product line only 
A customer has asked what single-origin coffees Sizwe sells. Return the SKU, product name, pack size 
and list price for every product in the Single Origin line, most expensive first. 
Answer 2 - One product line only 
Select*

Question 3 - Wholesale customers in two provinces 
The sales manager is planning a trip through Gauteng and the Western Cape. Return the customer ID, 
trading name, province, segment and credit limit for every Wholesale customer in either of those two 
provinces. Sort by province, then trading name. 
Answer 3 - Wholesale customers in two provinces 
Select*

Question 4 - The ten largest credit limits 
Credit control wants to review the biggest exposures first. Return the ten customers with the highest 
credit limit, showing their ID, trading name, province and limit. 
Answer 4 - The ten largest credit limits 
Select*

Question 5 - Orders in a single month 
Return every order placed in June 2025, showing the order ID, customer ID, order date, delivery date 
and channel, oldest first. 
Answer 5 - Orders in a single month 
Select*

## Part B - Aggregation

Question 6 - Customers per province 
How many customers does Sizwe have in each province? Return the province and the count, largest 
first. 
Answer 6 -  Customers per province 

Question 7 - Performance by SKU 
For each SKU, return the total units sold, the total revenue, and the average discount percentage. Sort 
by revenue, highest first. Round revenue to two decimals and the average discount to four. 
Answer 7 - Performance by SKU 

Question 8 - Only the SKUs that matter 
Take the previous query and keep only the SKUs with total revenue above R50 million. Also return how 
many order lines each one appears on. 
Answer 8 - Only the SKUs that matter 

Question 9 - Invoicing by month 
For FY2025 only (1 July 2024 to 30 June 2025), return the number of invoices raised each month and 
their total value. One row per month, in date order.
Answer 9 - Invoicing by month 

## Part C - Joins
## Part D - Subqueries and CTEs
## Part E - Window Functions
