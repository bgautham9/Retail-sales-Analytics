Retail Sales Analytics Dashboard (Power BI)
🚀 Project Overview
This project demonstrates how raw transactional retail data can be transformed into an interactive business intelligence dashboard using Power BI.

The dataset was intentionally messy and required extensive data cleaning, transformation, and modeling before building the final dashboard.

The final solution helps analyze sales performance, product demand, customer distribution, and order trends.

🧹 Data Preparation
Key data cleaning steps performed:

Trimmed and cleaned categorical text columns

Standardized inconsistent values (e.g., payment methods and order status)

Handled missing values

Created calculated columns like Delivery Days

Built a star schema data model

🏗 Data Model
The project follows a Star Schema architecture:

Fact Table:

Fact_Sales

Dimension Tables:

Dim_Customer

Dim_Product

Dim_Date

This structure improves query performance and analytical flexibility.

📊 Dashboard Features
Executive Overview
Total Revenue

Total Orders

Average Order Value

Return Rate

Product Performance
Revenue by Category

Top Products by Sales

Quantity Sold by Product

Customer Insights
Orders by City

Revenue by State

Device Type Distribution

Order Trends
Monthly Sales Trend

Delivery Performance

Return Analysis

⚙️ Technologies Used
Power BI

Power Query

DAX

Data Modeling (Star Schema)




