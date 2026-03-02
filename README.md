Title : Customer Retention and Revenue Analysis

A data analytics project focused on evaluating business revenue performance, identifying high-value customers, and analyzing customer retention behavior using Python and SQL.

Project Objective :

This project analyzes transactional sales data to:

Evaluate overall revenue performance

Identify high-value customers and key revenue contributors

Measure repeat purchase behavior and retention rate

Detect customers at risk of churn (> 90 days inactive)

Provide data-driven business recommendations

Dataset Overview :

Dataset: transactions.csv

Key Columns:

customer_id

order_id

order_date

quantity

price

Feature Engineering:

Created revenue column

revenue = quantity × price

Key Performance Indicators (KPIs) :

Total Revenue – Overall business performance

Monthly Revenue Trend – Growth & seasonality insights

Top 5 Customers – High-value customer identification

Repeat Purchase Rate – Customer retention strength

Churn Risk Customers – Inactive for more than 90 days

Revenue Analysis :

Calculated total revenue using:

SUM(quantity * price)

Aggregated revenue at the customer level

Identified top revenue-generating customers :

Analyzed monthly revenue trends using date aggregation

Validated results using both Python (Pandas) and SQL

Customer Retention Analysis :

Calculated number of unique orders per customer

Classified repeat customers (order_count > 1)

Computed repeat purchase rate :

Measured customer recency (days since last purchase)

Identified churn-risk customers (> 90 days inactive)

Tech Stack :

Python

Pandas

NumPy

Matplotlib / Seaborn

SQL

Jupyter Notebook

Sample Business Insights :

Revenue trends reveal business growth patterns

A small segment of customers contributes a large portion of revenue

Repeat customers drive long-term profitability

Early identification of churn enables proactive retention strategies

Business Recommendations :

Implement loyalty programs for high-value customers

Launch re-engagement campaigns for churn-risk customers

Monitor monthly revenue trends for forecasting

Focus on improving retention to increase customer lifetime value
