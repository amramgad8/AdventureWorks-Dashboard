# 🚴‍♂️ AdventureWorks Sales Dashboard

This Power BI dashboard offers an interactive and insightful view of AdventureWorks' sales performance across products, customers, categories, and regions. It is designed to support data-driven decision-making by presenting real-time KPIs and visual analytics.

---

## 📊 Overview

- **Total Revenue**: `$24.9M`
- **Total Profit**: `$10.5M`
- **Orders**: `25.2K`
- **Return Rate**: `2.2%`

### Key Highlights:
- Monthly Revenue: `$1.83M` (↑ +3.31%)
- Monthly Orders: `2,146` (↓ -0.88%)
- Monthly Returns: `166` (↑ +1.78%)

---

## 📈 Revenue & Orders Insights

- **Revenue Trending**: A steady upward trend since Jan 2020.
- **Orders by Category**:
  - Accessories: 17K
  - Bikes: 13.9K
  - Clothing: 7K
- **Top Products by Orders**:
  - Water Bottle - 30 oz.
  - Sport Helmets (Red, Blue, Black)
  - Road Tire Tube

- **Most Ordered Product Type**: `Tires and Tubes`
- **Most Returned Product Type**: `Shorts`

---

## 🌍 Regional Sales Analysis

Interactive map visualization highlighting regional performance across:

- **North America** (Highest: United States)
- **Europe** (UK, Germany, France)
- **Pacific** (Australia)

> Filter buttons allow quick selection by continent.

---

## 🛍️ Product Performance

**Selected Product Example**: `Water Bottle - 30 oz.`

- Monthly Orders: `404` vs Target `438`
- Monthly Revenue: `$4,067` vs Target `$4,292`
- Monthly Profit: `$2,546` vs Target
- Dynamic **Price Adjustment Slider**
- Metrics Available:
  - Orders
  - Revenue
  - Profit
  - Returns
  - Return %

📌 *Profit increased by 230.3% between Jun 2021 and Jun 2022.*

---

## 👥 Customer Analysis

- **Unique Customers**: `17.4K`
- **Avg Revenue per Customer**: `$1,431`
- **Top Customer**: `Mr. Maurice Shan`  
  - Orders: 6  
  - Revenue: `$12.4K`

### Demographics:
- By **Income**: Low / Average / High
- By **Occupation**: Professional / Skilled Manual / Management

---

## 🧩 Data Model

This report is built using a star schema for optimal performance.

### Fact Tables:
- `Sales Data`
- `Returns Data`

### Dimension Tables:
- `Calendar Lookup`
- `Customer Lookup`
- `Territory Lookup`
- `Product Lookup`
- `Product Subcategory Lookup`
- `Product Category Lookup`
- `Rolling Calendar`

> Relationships are established via surrogate keys to ensure consistency and efficient querying.

---

## 🛠️ Tech Stack

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query (M)**
- **Star Schema Modeling**

---

## 📌 Future Enhancements

- Predictive analytics for revenue forecasting
- Customer segmentation via clustering
- Inventory optimization suggestions
- Mobile responsive version

---

## 📥 How to Use

1. Clone this repo.
2. Open the `.pbix` file in Power BI Desktop.
3. Connect to your data source or use sample data.
4. Customize visuals, measures, or filters as needed.

---



> © AdventureWorks | Built for business intelligence and strategic insights.
