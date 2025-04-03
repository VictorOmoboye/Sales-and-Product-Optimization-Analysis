# DENNIS FURNISHING SUPPLIES SALES OPTIMIZATION ANALYSIS 
## Leveraging SQL Data Query Language for Data-Driven Analysis of Sales and Product Performance at Dennies Furnishing Supplies
![image](https://github.com/user-attachments/assets/4b11900f-531f-47ce-b024-84687dbd2b4e)

***Disclaimer⚠️:** All info and reports in this repository do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual. All info are dummy and design to demonstrate my capabilities of using SQL to perform advance analytics*
## INTRODUCTION
This project presents a comprehensive analysis of sales performance, product inventory, and customer behavior trends for Dennis Furnishings Supplies, a company operating across multiple U.S. cities, specializing in office supplies, furnishings, and equipment. By leveraging historical data, the analysis assesses year-over-year sales trends, optimizes product offerings, and uncovers key customer behavior patterns across various regions. SQL Data Query Language (DQL) is utilized to derive actionable insights, facilitating data-driven decision-making to enhance business strategies and improve operational efficiency.
![image](https://github.com/user-attachments/assets/a7fe46c7-e0c5-4e10-b258-4034b0dff659)

## PROBLEM STATEMENT
As Dennis Furnishings Supplies continues to expand, it is essential to gain a deeper understanding of business performance across various product categories and customer segments. The company needs to identify the top-performing products driving the highest sales, determine which properties are placing the most orders, and uncover underperforming categories. This knowledge is crucial for optimizing operational efficiency and driving sustained growth.

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
I visualize the logical schema through an Entity-Relationship Diagram (ERD) to effectively convey the logical constraints and associations within the database. This approach enhances my understanding of the organization of the tables and their interrelationships, revealing that the dataset comprises three distinct tables: **Orders**, **Products**, and **PropertyInfo**. These tables are interconnected through primary and foreign key relationships, enabling seamless data retrieval and analysis. The ERD serves as a foundational tool for identifying how data flows between entities, ensuring clarity in the modeling process and supporting the overall analysis of sales performance and customer behavior trends for Dennis Furnishing Supplies.
![image](https://github.com/user-attachments/assets/cb155d10-bb09-4c2a-b777-d4f10d32648c)

## DATA ANALYSIS
This query retrieves a comprehensive dataset that encompasses all relevant details about orders, products, and properties. By joining the **Orders**, **Products**, and **PropertyInfo** tables, it provides a holistic view of each order, including information such as order IDs, product names, categories, pricing, quantities ordered, and the associated property details. This integrated output enables a thorough analysis of sales performance and customer behavior, facilitating data-driven decision-making for Dennis Furnishing Supplies.

![image](https://github.com/user-attachments/assets/d0837298-ae17-4fee-a33d-4b19e86027c9)



This query outputs the cities and states where Dennis Office Supplies properties are located, revealing that the company operates across 20 states in the United States. By providing a detailed view of the geographic distribution of these properties, the query allows for better understanding of the company’s market presence and customer reach, enabling targeted strategies for sales and inventory management in different regions.

![image](https://github.com/user-attachments/assets/d7ed9c74-3d8c-4069-9678-63263952b2d2)




This query presents the data output of the various product categories available at Dennis Furnishing Supplies, highlighting a total of five distinct categories. By showcasing these categories, the query provides insights into the product diversity within the store, allowing for a better understanding of inventory composition and potential areas for growth or optimization in product offerings.

![image](https://github.com/user-attachments/assets/09519594-e3c8-4966-8255-194c90427210)




This query outputs the product categories along with the corresponding number of products in each category. The results reveal that **Furnishings** leads with the highest count of 26 products, followed by **Public Areas**, while **Office Supplies** has the lowest count with 13 products. This analysis offers valuable insights into the distribution of products across categories, helping to identify areas of focus for inventory optimization and potential adjustments in product availability.

![image](https://github.com/user-attachments/assets/98ea7edb-8cfc-46b5-a5fc-24e9ef23a45b)




This query reveals the five most expensive products, with the **King Bed** priced highest at $300, followed by the **Double Bed**. On the lower end, **Washcloth**, **Flyer Holder**, and **Paper Clips** are among the least expensive products, each priced at $3. This analysis highlights the pricing distribution of products, offering insights into premium versus budget product categories and helping guide pricing strategies and sales focus.

![image](https://github.com/user-attachments/assets/9f067ab4-2f1e-48c2-9777-675277913f78)



This query displays the average price of products in each category, revealing that **Furnishings** has the highest average price at $83.65, followed by **Public Areas**. In contrast, **Office Supplies** has the lowest average price at $22.69, largely due to the quantity and nature of products in that category. This analysis provides insights into price distribution across categories, helping to understand the value of products offered and informing pricing and inventory strategies.

![image](https://github.com/user-attachments/assets/8a0dc9b7-9aeb-4e08-b522-1df491db5fb7)


This query extracts the names and categories of products priced above $200, revealing four products that meet this criterion: **Bed (King)**, **Bed (Double)**, **Leaf Blower**, and **Sofa**. This analysis helps identify premium products within the inventory, offering insights into high-value items that can be targeted for marketing or sales promotions.

![image](https://github.com/user-attachments/assets/91a670b7-2879-43e6-8bca-505694324f09)


This query displays the total quantity of products ordered in **2015** and **2016**, revealing that **5,015** products were ordered in 2015 and **5,081** products were ordered in 2016. This analysis indicates a slight increase in product demand over the two years, providing valuable insights into sales trends and helping to forecast future inventory needs.

![image](https://github.com/user-attachments/assets/4b46be7a-8ac1-4680-8029-34b1346a7abe)


This query evaluates whether a product's price is more than $200, creating a new column that indicates if a product is "**Above 200**" or "**Below or Equal to 200**." The results reveal that only **4 products** out of **94 product categories** fall into the "**Above 200**" category, while the majority are priced "**Below or Equal to 200**." This classification provides a clear view of the distribution of high-value versus more affordable products, aiding in pricing strategy and product segmentation.

![image](https://github.com/user-attachments/assets/04cd53c6-b871-4f56-b6c0-ace06c1851ca)


## RECOMMENDATION
Here are some strategic recommendations based on the insights drawn from the dataset using SQL queries:

- **Focus on High-Value Products**: With only 4 products priced above $200, consider targeted marketing strategies for these premium items (e.g., King Bed, Double Bed, Leaf Blower, Sofa) to maximize revenue from high-value sales.

- **Optimize Inventory for Popular Categories**: Furnishings have the highest product count and average price. Ensure adequate stock and consider expanding the range in this category to meet demand.

- **Adjust Pricing Strategy**: Since Office Supplies have the lowest average price ($22.69), explore opportunities for bundle deals or price adjustments to increase profitability without losing volume.

- **Monitor Sales Trends**: The slight increase in total orders from 2015 (5,015) to 2016 (5,081) suggests a growing demand. Use this trend to forecast future inventory needs and adjust production accordingly.

- **Expand Presence in High-Demand Locations**: Analyze the data on properties across 20 states and focus on regions with the highest sales for targeted marketing efforts and expanding the distribution network.

- **Diversify Product Offerings in Low-Performing Categories**: For categories that are underperforming in terms of sales volume, consider introducing new products or discontinuing low-demand items to optimize the product range.

- **Regularly Reevaluate Product Pricing**: Use the price classification data to periodically reassess product pricing strategies, ensuring alignment with market demand and competition.

These recommendations aim to guide stakeholders at Dennis Furnishing Supplies toward more data-driven decisions for maximizing sales, optimizing inventory, and improving overall business performance.

## THANK YOU
For more information, you can contact me
![image](https://github.com/user-attachments/assets/400a6867-54ca-409f-b788-6d12b14d0833)
