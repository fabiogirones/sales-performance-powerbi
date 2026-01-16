# Sales Performance & Business Dashboard (Power BI)

## 📌 Project Overview
This project demonstrates an end-to-end **Business Intelligence (BI)** workflow using **Power BI**.  
The goal is to transform raw sales data into meaningful **KPIs, insights, and business recommendations** through data modeling, DAX measures, and interactive dashboards.

The dashboard is designed for **management and business stakeholders** to quickly assess sales performance across time, products, and regions.

---

## 📥 Dataset Used

**Global Electronics Retailer**  
This dataset contains transactional and dimensional tables for a fictional global electronics retailer, including details on transactions, products, customers, store locations, and currency exchange rates.

Data source:  
🔗 https://mavenanalytics.io/data-playground/global-electronics-retailer

---

## 🎯 Business Objective
- Monitor overall sales and revenue performance
- Understand patterns by product, geography, and time
- Support management decisions with key metrics
- Uncover trends like seasonality and customer behavior

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **Power Query** (data preparation & transformation)
- **DAX** (measure creation & KPI calculations)
- **SQL** (optional for data extraction/queries)
- CSV files for data input

---

## 🔄 Data Preparation
Data preparation was performed in **Power Query** and included:
- Cleaning and standardizing columns
- Parsing dates correctly
- Removing duplicates
- Creating a star schema (fact + dimension tables)
- Handling missing values

Star schema structure:
- Fact table: `Sales`
- Dimension tables: `Products`, `Customers`, `Stores`, `Calendar`, `CurrencyRates`

---

## 📐 Key DAX Measures
Some of the business metrics featured in the dashboard:

| Measure Name | Description |
|--------------|-------------|
| **Total Revenue** | Total revenue across all transactions |
| **Total Orders** | Number of unique orders |
| **Average Order Value (AOV)** | Average value per order |
| **Month-over-Month Growth %** | Measures growth compared to previous month |
| **Revenue by Region / Product** | Breakdowns to compare performance |

All measures are stored in a dedicated **Measures table** for maintainability and clarity.

---

## 📊 Dashboard Highlights

### 📈 Executive Overview
- Total Revenue
- Monthly growth
- Average Order Value
- Revenue trend over time

### 🛍 Product Performance
- Revenue by product category
- Top / bottom performing products

### 🌍 Regional Performance
- Revenue by country / store region
- Comparison of growth rates

---

## 💡 Key Insights (example)
- A limited number of product categories generate the largest portion of revenue
- Certain regions show stronger growth trends
- Seasonal patterns are visible across the year

---

## 📌 Business Recommendations
- Prioritize marketing for high-value product categories
- Expand successful strategies in top-performing regions
- Plan inventory based on seasonal demand insights

---

## 📷 Dashboard Previews
Screenshots of the dashboard are included in the `/powerbi` folder so recruiters and stakeholders can see the visual output without needing Power BI installed.
