# SQL--Retail-analysis
Executed SQL queries to clean and analyze sales data for a retail e-commerce website, enhancing data quality and providing actionable insights into product performance and trends.

Performed a series of SQL tasks to clean and analyze sales data, utilizing functions such as ROW_NUMBER() and DELETE to remove duplicate records, JOIN and UPDATE to correct pricing discrepancies, and IS NULL with UPDATE to handle null values.

Utilized STR_TO_DATE() to clean date formats, SUM() and GROUP BY to summarize total sales, and COUNT() to analyze purchase frequency.

Developed and maintained comprehensive sales dashboards and business MIS reports, regularly updating leadership on performance trends and actionable insights.

Key Achievements:
Removing Duplicates: Identified and removed duplicate records in the sales_transaction table using ROW_NUMBER() and DELETE.

Fixing Incorrect Pricing: Corrected pricing discrepancies between sales_transaction and product_inventory tables using JOIN and UPDATE.

Handling Null Values: Replaced null values in the customer_profiles table with “Unknown” using IS NULL and UPDATE.

Cleaning Date Column: Standardized the TransactionDate column by converting it from text to date format using STR_TO_DATE().

Total Sales Summary: Summarized total sales and quantities sold per product using SUM() and GROUP BY.

Customer Purchase Frequency: Counted the number of transactions per customer using COUNT() and GROUP BY.

Product Category Performance: Evaluated performance of product categories based on total sales using SUM() and GROUP BY.

High and Low Sales Products: Identified top 10 products with highest total sales and bottom 10 products with least units sold using SUM(), ORDER BY, and LIMIT.

Sales Trends: Analyzed sales trends by tracking daily transactions, units sold, and total sales using COUNT(), SUM(), and GROUP BY.

Growth Rate of Sales: Calculated month-on-month growth rate of sales using EXTRACT(MONTH FROM date_column), SUM(), and LAG().

Customer Segmentation: Segmented customers based on the total quantity of products purchased using SUM(), CASE, and COUNT().
