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
![Screenshot 2024-10-05 174600](https://github.com/user-attachments/assets/c4153162-6040-4808-b4b0-cc84589a5f91)



This query outputs the cities and states where Dennis Office Supplies properties are located, revealing that the company operates across 20 states in the United States. By providing a detailed view of the geographic distribution of these properties, the query allows for better understanding of the company’s market presence and customer reach, enabling targeted strategies for sales and inventory management in different regions.

![image](https://github.com/user-attachments/assets/e375ae28-db28-4f6d-856a-553a1e75f0a2)



This query presents the data output of the various product categories available at Dennis Office Supplies, highlighting a total of five distinct categories. By showcasing these categories, the query provides insights into the product diversity within the store, allowing for a better understanding of inventory composition and potential areas for growth or optimization in product offerings.
![image](https://github.com/user-attachments/assets/6cf2e833-a004-4492-b795-8425c8fdb6ee)



This query outputs the product categories along with the corresponding number of products in each category. The results reveal that **Furnishings** leads with the highest count of 26 products, followed by **Public Areas**, while **Office Supplies** has the lowest count with 13 products. This analysis offers valuable insights into the distribution of products across categories, helping to identify areas of focus for inventory optimization and potential adjustments in product availability.

![image](https://github.com/user-attachments/assets/8a9b123d-fdf9-4761-ba96-e8e14492ce51)



This query reveals the five most expensive products, with the **King Bed** priced highest at $300, followed by the **Double Bed**. On the lower end, **Washcloth**, **Flyer Holder**, and **Paper Clips** are among the least expensive products, each priced at $3. This analysis highlights the pricing distribution of products, offering insights into premium versus budget product categories and helping guide pricing strategies and sales focus.

![image](https://github.com/user-attachments/assets/9f067ab4-2f1e-48c2-9777-675277913f78)









This query displays the average price of products in each category, revealing that **Furnishings** has the highest average price at $83.65, followed by **Public Areas**. In contrast, **Office Supplies** has the lowest average price at $22.69, largely due to the quantity and nature of products in that category. This analysis provides insights into price distribution across categories, helping to understand the value of products offered and informing pricing and inventory strategies.
![image](https://github.com/user-attachments/assets/8a0dc9b7-9aeb-4e08-b522-1df491db5fb7)




