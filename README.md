# E-commerce-Sales-Analysis
Overview
Objective: To analyze e-commerce sales data to identify key sales trends, customer behavior, and product performance. The goal is to deliver actionable insights for improving sales strategies and customer engagement.
Data Cleaning: The data was cleaned by handling duplicates, verifying data types, and transforming specific fields like Discount, Order Date, and Ship Date. Custom columns such as Product Amount and Sales Amount were created.
Data Analysis: DAX measures were applied to calculate total sales, average order value (AOV), total orders, and customer metrics. Trends in sales, quantity, and discounts were analyzed over time.
Data Visualization: Various Power BI visuals were created, including bar charts, line charts, donut charts, and card visuals, to represent key metrics such as sales, profit margin, and regional performance.
Insights: Key insights include the impact of discounts on sales, customer segmentation by region, and performance variations across product categories and sales channels.
Deliverable: A comprehensive Power BI report visualizing the sales, customer demographics, and product performance. The dashboard provides interactive filtering options for users to explore different segments.
Extended Overview
 

Data Collection & Cleaning:
Removing duplicates (e.g., Customer ID, Product ID).
Verifying and correcting data types (e.g., Date, Discount, and Quantity fields).
Filtering out zero values in the Quantity column and creating new columns for discount categories (No Discount, Low, Medium, High).
Data was collected from several tables: Customers, Dates, Products, and Sales.
The dataset underwent several cleaning steps such as:
Custom columns like Product Amount (Quantity * List Price) and Sales Amount (Product Amount - Discount) were added for further analysis.
Data Analysis:
Total Sales: Sum of sales amounts.
Total Orders: Distinct count of orders.
Average Order Value (AOV): Total sales divided by total orders.
Average Items per Order (AIPO): Total quantity sold divided by total orders.
Revenue per Customer (ARPC): Total sales divided by the number of customers.
DAX measures were created for:
Additional calculations such as Total Profit and Profit Margin were derived to assess the profitability of the business.
A Discount Category was created to analyze the impact of different discount levels on sales.
Data Visualization:
Card Visuals were created to show aggregate metrics like total sales, quantity sold, orders, and customers.
Line Chart was used to visualize sales trends over time.
Stacked Bar Charts were used to compare total sales by customer segment and product category across different regions.
Donut Chart visualized the distribution of orders by shipping method, and Matrix Visuals were used to analyze sales by discount levels and product categories.
Gauge Visuals showed average discount and delivery time metrics.
Trend Analysis:
A sales trend analysis was conducted to examine the relationship between order quantities and sales over time, highlighting the effects of promotional campaigns and seasonal sales.
Profit margin trends were analyzed to evaluate how discounts affected profitability across different product categories.
Summary:
Discount Impact: Higher discounts generally led to increased sales but reduced profit margins, particularly for certain product categories like Furniture and Office Supplies.
Regional Performance: Certain regions showed higher sales in specific product categories, allowing for better-targeted marketing strategies.
Order Fulfillment & Delivery: Shipping methods like Standard Class and Second Class had the highest order volumes, whereas Same Day deliveries had the highest profit margins.
The analysis revealed several key insights:
The Power BI report serves as an interactive dashboard, enabling stakeholders to explore various aspects of sales performance, customer segmentation, and discount strategies.
Data Collection & Cleaning:

Data was collected from two primary tables: Customer_Details and Loan_Details. The data was categorized into age groups, income brackets, credit score buckets, and loan types.
Data Categorization:
Age Groups: Categorized into Young, Middle-aged, Senior, and Elder.
Credit Score: Divided into Poor, Fair, Good, Very Good, and Excellent.
Income: Segmented into Low, Medium, and High based on income ranges.
Data types were verified, and the necessary changes were made to ensure the proper categorization and formatting for analysis.
Data Analysis:

Various DAX measures were created to calculate key metrics:
Total Loan Amount: The sum of all loan amounts.
Average Monthly Installment: The average of monthly loan payments.
Defaulted Loans: The number of loans that have defaulted.
High-Risk Loans: Loans that are at high risk based on credit score.
Loan Status: Categorized by Active, Closed, and Defaulted.
Relationships were established between Customer_Details, Loan_Details, and Date tables for more comprehensive analysis.
.
Data Visualization:

Customer Demographics:
Pie Charts were used to display gender distribution and education level of customers.
Clustered Bar Chart explored the relationship between gender, education level, and credit score.
Loan Portfolio & Performance:
Pie Chart displayed the distribution of loan types.
The 100% Stacked Column Chart was used to break down loans by type and status.
Tables were created to list top loans by amount, categorized by status (Active, Defaulted).
Financial Risk Analysis:
Pie Charts displayed defaulted loan amounts based on employment type and credit score.
Matrix visualizations revealed the relationship between income, education level, and the amount of defaulted loans.
Stacked Column Chart examined the number of customers by credit score and employment type.
Trend Analysis:

The financial risk analysis showed that customers with lower credit scores and incomes were more likely to default, with High Risk loans showing a direct correlation with poor credit scores and high loan amounts.
Risk Category: The High Risk category included those with credit scores below 580, and this group contributed significantly to the total defaulted loan amounts.
Summary:

Key insights showed that the default rates and loan amounts were higher in the lower income and lower credit score categories.
Customers with poor credit scores (below 580) represented the highest default risk, making them a focal point for risk mitigation strategies.
The Power BI dashboard provides an interactive tool for stakeholders to monitor customer demographics, loan performance, and financial risks, aiding in better decision-making for loan approvals and financial planning.
