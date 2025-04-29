# TASK-6-



I performed a sales trend analysis by first creating a table called online_sales with sample order data, including order dates, amounts, and product IDs. Using SQL in SQLite, I extracted the year and month from the order_date field with the strftime('%Y-%m', order_date) function. Then, I grouped the data by month, calculated the total revenue using SUM(amount), and determined the order volume using COUNT(DISTINCT order_id). Finally, I ordered the results chronologically to observe the monthly sales trends for 2023.
