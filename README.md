# DENNIS FURNISHING SALES OPTIMIZATION ANALYSIS 
## Leveraging SQL Data Query Language for Data-Driven Analysis of Sales and Product Performance at Dennies Furnishing
![image](https://github.com/user-attachments/assets/a7fe46c7-e0c5-4e10-b258-4034b0dff659)
## INTRODUCTION
This project presents a comprehensive analysis of sales performance, product inventory, and customer behavior trends for Dennis Furnishings, a company operating across multiple U.S. cities, specializing in office supplies, furnishings, and equipment. By leveraging historical data, the analysis assesses year-over-year sales trends, optimizes product offerings, and uncovers key customer behavior patterns across various regions. SQL Data Query Language (DQL) is utilized to derive actionable insights, facilitating data-driven decision-making to enhance business strategies and improve operational efficiency.

## PROBLEM STATEMENT
As Dennis Furnishings continues to expand, it is essential to gain a deeper understanding of business performance across various product categories and customer segments. The company needs to identify the top-performing products driving the highest sales, determine which properties are placing the most orders, and uncover underperforming categories. This knowledge is crucial for optimizing operational efficiency and driving sustained growth.

## AIM OF THE PROJECT
- Analyze sales trends and performance across product categories such as office supplies and furnishings.
- Identify high performing and underperforming products to optimize inventory.
- Evaluate customer orders and understand the distribution of sales across properties and regions.
- Provide a clear understanding of year over year sales performance using SQL queries and visualizations.
- Use insights to make recommendations for enhancing business profitability.

## SKILL & CONCEPT DEMOSTRATED
- **Business Overview:** Understanding the business, and their expectations.
- **Data Overview:** Looking into the data and exploring it’s relevance to the business.
- **Data Extraction:** Extract product, order, and customer data from the company's DataBase.
- **SQL Queries:** Write SQL queries to extract key metrics and insights from the data.
- **Recommendations:** Provide business recommendations based on the analysis.

## SQL TOOLS AND FEATURES
- **SQL QUERIES:** Extract relevant data from the Products, Orders, and PropertyInfo tables.
- **JOINS:** Combine data across tables to create comprehensive views of orders, products, and customers.
- **AGGREGATIONS:** Use SQL functions like SUM(), AVG(), and COUNT() to calculate key metrics such as total sales and product quantities.
- **FILTERING AND
GROUPING:** Apply SQL WHERE clauses and GROUP BY to filter and segment data by product category, region, and year.

## MODELLING
I visualize the logical schema through an Entity-Relationship Diagram (ERD) to effectively convey the logical constraints and associations within the database. This approach enhances my understanding of the organization of the tables and their interrelationships, revealing that the dataset comprises three distinct tables: **Orders**, **Products**, and **PropertyInfo**. These tables are interconnected through primary and foreign key relationships, enabling seamless data retrieval and analysis. The ERD serves as a foundational tool for identifying how data flows between entities, ensuring clarity in the modeling process and supporting the overall analysis of sales performance and customer behavior trends for Dennis Office Supplies.
![image](https://github.com/user-attachments/assets/cb155d10-bb09-4c2a-b777-d4f10d32648c)

## Data Analysis
This query retrieves a comprehensive dataset that encompasses all relevant details about orders, products, and properties. By joining the **Orders**, **Products**, and **PropertyInfo** tables, it provides a holistic view of each order, including information such as order IDs, product names, categories, pricing, quantities ordered, and the associated property details. This integrated output enables a thorough analysis of sales performance and customer behavior, facilitating data-driven decision-making for Dennis Office Supplies.
![image](https://github.com/user-attachments/assets/ed604e89-22fd-4057-a665-2c46dd1f9a0d)
