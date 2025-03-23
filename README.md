# Monday-Coffee-sales-using-PostgreSQL


**Objective**
The purpose of this project is to conduct a comprehensive analysis of Monday Coffee’s online sales data from January 2023 onwards. By examining consumer demand, sales trends, and market insights, we aim to recommend the top three major cities in India for opening new coffee shop locations. This analysis employs PostgreSQL to manage, transform, and analyze data effectively, providing meaningful insights for strategic decision-making.

**Key Questions**
The SQL code addresses the following critical business queries:

Coffee Consumers Count- Estimation of coffee consumers in each city, assuming 25% of the population consumes coffee.

Total Revenue from Coffee Sales- Calculation of total revenue from coffee sales across all cities during the last quarter of 2023.

Sales Count for Each Product- Breakdown of the number of units sold for each coffee product.

Average Sales Amount per City- Determination of the average sales amount per customer in each city.

City Population and Coffee Consumers- Compilation of city data including population and the estimated coffee consumer count.

Top Selling Products by City- Identification of the top three selling coffee products in each city based on sales volume.

Customer Segmentation by City- Counting the number of unique customers in each city who have purchased coffee products.

Average Sale vs Rent- Comparison of the average sales per customer and average rent per customer across all cities.

Monthly Sales Growth- Computation of the percentage growth or decline in sales across different months.

Market Potential Analysis- Identifying the top three cities based on metrics like total sales, total rent, total customers, and estimated coffee consumers.

**SQL Tasks Description**
The queries executed in the SQL file reflect an industry-level approach, emphasizing accuracy and actionable insights:

Data Preparation & Cleaning Consolidated and cleaned multiple datasets to ensure consistency and eliminate duplicate entries. Handled null values, standardized formats, and transformed raw data into a structured format.

Revenue and Sales Analysis Designed SQL queries to calculate revenue metrics, product sales counts, and average sales values for each city.

Consumer Insights Derived customer segmentation data to estimate the coffee consumer population per city, along with identifying buying trends and behaviors.

Advanced Aggregations and Rankings Used SQL ranking functions (e.g., RANK()) and group aggregations to pinpoint the top-performing cities and products.

Market Potential Evaluation Combined calculated metrics (e.g., revenue, rent, customer count) into a holistic analysis for recommending optimal city locations for expansion.

**Recommendations**
Based on the analysis conducted, the following cities are recommended for new store openings:

📍 City 1: Pune

Lowest average rent per customer.

Highest total revenue from coffee sales.

High average sales amount per customer.

📍 City 2: Delhi

Largest estimated coffee consumer population (7.7 million).

Highest total customer count (68).

Average rent per customer is affordable at ₹330.

📍 City 3: Jaipur

High customer count (69).

Extremely low average rent per customer (₹156).

Strong average sales per customer (₹11.6k).

**Key SQL Features Used**
PostgreSQL Functions: Leveraged aggregate functions (SUM, AVG), ranking functions (RANK), and complex subqueries to derive meaningful insights.

Data Transformation: Cleaned, joined, and transformed data to enable efficient querying.

Performance Optimization: Incorporated indexing and efficient joins for handling large datasets.

Dynamic Segmentation: Created flexible queries for customer segmentation and product analysis.

**Insights and Learnings**
This project provided hands-on experience in:

Real-world sales and market analysis using PostgreSQL.

Turning raw data into meaningful insights that drive business decisions.

Using SQL for end-to-end analytics—spanning data cleaning, modeling, and reporting.
