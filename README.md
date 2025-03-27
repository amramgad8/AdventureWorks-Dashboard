📊 AdventureWorks Sales Dashboard
Overview
This Power BI dashboard provides a comprehensive and interactive analysis of the AdventureWorks sales data, enabling business stakeholders to monitor key performance metrics, customer behavior, product performance, and regional sales distribution. The dashboard is built on a well-structured star schema data model to ensure optimal performance and scalability.

📌 Key Features
1. Executive Summary (Overview Page)
Total Revenue: $24.9M

Total Profit: $10.5M

Total Orders: 25.2K

Return Rate: 2.2%

Highlights:

Revenue Trend: A clear upward trajectory from Jan 2020 to mid-2022.

Orders by Category: Accessories lead with 17K+ orders, followed by Bikes and Clothing.

Top Products: Water Bottle – 30 oz. is the most ordered product.

Monthly KPIs: Monitors changes in revenue, orders, and returns month-over-month.

Most Ordered & Most Returned Product Types:

Most Ordered: Tires and Tubes

Most Returned: Shorts

2. Geographical Sales Analysis
Visualizes sales performance across North America, Europe, and Pacific regions.

Interactive map highlights the highest-performing regions, with the United States as the leading contributor.

Quick filters for selecting specific continents for focused analysis.

3. Product-Level Deep Dive
Focuses on selected product (e.g., Water Bottle – 30 oz.).

Tracks monthly performance against targets:

Orders

Revenue

Profit

Simulates impact of price adjustments on profit using dynamic sliders.

Shows adjusted profit vs total profit trends.

Custom metric selection: Orders, Revenue, Profit, Returns, Return %.

4. Customer Insights
Unique Customers: 17.4K

Average Revenue per Customer: $1,431

Top Customers:

Highest spender: Mr. Maurice Shan with $12.4K across 6 orders.

Analysis by:

Income Level (Low, Average, High)

Occupation (Professional, Skilled Manual, Management)

Revenue & customer base trend over time with year filters.

🧩 Data Model (Star Schema)
The dashboard is powered by a robust data model consisting of:

Fact Tables:
Sales Data: Order details, quantities, prices, and revenue.

Returns Data: Product returns, dates, and territory info.

Dimension Tables:
Calendar Lookup: Date hierarchy, including day, month, and year.

Customer Lookup: Customer demographics including income and occupation.

Territory Lookup: Country, region, and continent information.

Product Lookup: Detailed product attributes and pricing.

Product Subcategories & Categories

Rolling Calendar: Used for time intelligence metrics like MoM, QoQ.

All tables are connected via surrogate keys ensuring referential integrity and efficient querying.

💡 Business Value
This dashboard empowers decision-makers to:

Track profitability trends and return rates.

Identify high-performing and underperforming products.

Understand customer demographics and behavior.

Optimize inventory and pricing strategies.

Make region-specific marketing and sales decisions.

🔧 Tools & Technologies
Power BI (Data visualization and modeling)

DAX (For calculated columns, measures, and KPIs)

Power Query (M Language) (ETL processes and data transformation)

📈 Suggested Enhancements
Integrate forecasting models for revenue and returns.

Add customer segmentation using clustering.

Include drill-through for individual product and customer views.
