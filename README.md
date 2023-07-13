
# Sales Analytics Dashboard

The company's sales analysis was carried out using Microsoft Power BI tool which involved ETL tools, Data Manipulation, DAX Functions, and a responsive Dashboard representing revenue insights and profit insights from sales data. 

## Contents 
* Business Objective
* Data Understanding
* Solution
* Tools 
## Business Objective

 - The main objective is to create a dashboard using BI tool to understand issues with their Sales and design a strategy to tackle the problem. 
 - Sales data of a company for four years had to be evaluated to find the trends and patterns affecting a company's revenue.
## Data Understanding
 The given [dataset](https://github.com/somesh041/Sales-Analytics-Dashboard/blob/master/Sales%20Transactions.xlsx) of sales had 148395 rows and 11 features which were semi-structured. Supporting datasets contained information of sales regarding [Date](https://github.com/somesh041/Sales-Analytics-Dashboard/blob/master/Sales%20Date.xlsx), [Markets](https://github.com/somesh041/Sales-Analytics-Dashboard/blob/master/Sales%20Markets.xlsx) , [Cutomer type](https://github.com/somesh041/Sales-Analytics-Dashboard/blob/master/Sales%20Customers.xlsx) and [Products](https://github.com/somesh041/Sales-Analytics-Dashboard/blob/master/Sales%20Products.xlsx). 
The dataset was completely labeled and had Numerical columns and categorical columns. 

The features present in the data are:
- product_code
- customer_code
- market_code
- order_date
- sales_qty
- sales_amount	
- currency	
- norm_sales_amount	
- ProfitMargin%	
- Profit_Margin	
- Cost_Price
Relations were created for the remaining datasets that joined the Sales Transactions dataset with one to many relation.
![Relations](https://github.com/somesh041/Sales-Analytics-Dashboard/blob/master/Relation.jpg) 



## Solution

The evident decline in the company's sales indicates a need for strategic analysis as an analyst. Based on the current situation, several key suggestions can be drawn to address the issue effectively:

1. Enhance Product Quality: Devote attention to improving the quality of products or services offered. Focus on delivering superior value, durability, and customer satisfaction.

2. Strengthen Advertising and Promotions: Invest in impactful marketing campaigns to create awareness and generate demand. Utilize targeted advertising channels, compelling messaging, and persuasive promotional strategies to attract customers.

3. Foster Healthy Communication between Management and Suppliers: Establish open lines of communication with suppliers to ensure a smooth and efficient supply chain. Build strong relationships, negotiate favorable terms, and collaborate on optimizing procurement processes.

4. Enhance Product Aesthetics (Packaging): Enhance the visual appeal and packaging of products to attract customers' attention and differentiate them from competitors. Engaging packaging designs can positively influence purchasing decisions.

5. Identify Location-Based Demand: Analyze market data to identify specific geographic areas with higher demand potential. Tailor marketing efforts, product assortments, and distribution strategies to effectively cater to the unique needs and preferences of each location.

6. Uncover Market Dynamics and Driving Forces: Investigate which particular markets are driving the chain of demand for location-based needs. Understand the underlying factors that contribute to market growth, such as demographics, economic conditions, and consumer behavior.

By implementing these business-oriented recommendations, the company can proactively address the declining sales trend and position itself for growth and success in the market.
## Tools
This Sales analytics dashboard utilizes the following technologies and tools:
* Power BI
* Power Query
* DAX Functions
* Microsoft EXCEL
