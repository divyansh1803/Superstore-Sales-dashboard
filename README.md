# Superstore-Sales-dashboard
# 🛒 Superstore Sales Dashboard

This repository contains a Power BI dashboard project that analyzes retail performance data from a fictional Superstore. The goal of this project is to provide key insights into sales trends, customer segments, regional performance, and product profitability across various business categories.

---

## 📄 Abstract

The **"Superstore Sales Dashboard"** project provides an interactive business intelligence report built using Power BI. The dashboard visualizes critical retail metrics such as sales, profit, quantity sold, customer segments, and shipping modes. It supports decision-making by identifying top-performing regions, products, and customer categories. By analyzing historical sales data, the dashboard offers strategic insights to optimize operations and improve profitability in a retail business context.

---

## 🚀 Key Features

- 📊 **Sales KPIs:** Total Sales, Profit, Quantity, Discount, and Profit Ratio.
- 🗺️ **Regional Performance:** Sales and profit analysis by state, city, and region.
- 🧑‍🤝‍🧑 **Customer Segmentation:** Insights by Segment (Consumer, Corporate, Home Office).
- 🛍️ **Category Trends:** Top/Bottom products, Sub-Category performance.
- ⏱️ **Time Series Analysis:** Monthly and yearly sales/profit trends.
- 🚚 **Shipping Performance:** Mode-wise delivery and cost analysis.
- 📈 **Dynamic Filters:** Slicers for Year, Region, Category, Segment, and Product.

---

## 🧰 Technology Stack

| Layer | Technology | Purpose |
|-------|------------|---------|
| **Data Source** | Excel / CSV (Superstore Dataset) | Transactional retail data including orders, returns, shipping, and customers |
| **Data Processing** | Power BI Query Editor | Cleaning and transforming raw data |
| **Data Visualization** | Power BI Desktop | Building interactive dashboards |
| **Data Modeling** | Power BI + DAX | Relationships, measures (e.g., profit ratio, YoY change), calculated columns |
| **Version Control** | Git + GitHub | Repository management, collaboration |
| **Documentation** | Markdown (`README.md`) | Project description, methodology, and insights |

---

## 📈 Methodology

1. **Data Collection**  
   The dataset used is the Global Superstore dataset, typically containing order-level information such as product, region, sales, profit, and shipping.

2. **Data Cleaning**  
   - Removed missing or inconsistent entries using Power BI Query Editor.
   - Standardized date formats and categorical fields (e.g., Segment, Region).

3. **Data Modeling**  
   - Built a star schema with fact tables (Sales) and dimension tables (Customer, Product, Ship Mode).
   - Created calculated measures using DAX for Sales, Profit, Discount %, Profit Ratio, etc.

4. **Dashboard Design**  
   - Designed visuals for executives and operations managers.
   - Included drill-downs, filters, and conditional formatting for insights.

5. **Insights Extraction**  
   - Identified top-selling products and underperformers.
   - Analyzed regional and segment-based profitability.
   - Tracked seasonal sales trends and high-return zones.

---

## 📂 Repository Structure

superstore-sales-dashboard/
├── Superstore_Sales.pbix # Power BI dashboard file
├── data/
│ └── superstore_orders.csv # Raw dataset (if shared)
├── images/
│ └── dashboard_preview.png # Dashboard preview image
├── README.md # Project documentation
└── LICENSE # Optional license file


