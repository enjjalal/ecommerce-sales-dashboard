# 📊 Project Summary: E-Commerce Sales Performance Dashboard

## 📝 Problem Statement
Management wants to understand overall sales performance:
- Which products and categories drive the most revenue?  
- Do sales vary by season or region?  
- Do discounts improve or hurt profit margins?  

Key questions:  
1. How much total revenue, profit, and number of orders did we make?  
2. Which products and categories are the top performers?  
3. Do sales increase or decrease in certain months or seasons?  
4. Do discounts help us make more money, or do they reduce profit margins?  

---

## 📌 KPI Blueprint

### Core Profitability KPIs
- `Total Profit = SUM(Profit)`
- `Profit Margin % = Profit ÷ Revenue`
- `Profit per Order = Profit ÷ Number of Orders`
- Top Products by Profit
- Top Categories by Profit

### Supporting Revenue/Volume KPIs
- `Total Revenue = SUM(Sales)`
- `Number of Orders`
- `Average Order Value (AOV) = Revenue ÷ Orders`
- Revenue Trend by Month/Quarter
- Regional Revenue & Profit Comparison

### Discount Analysis (A/B Testing KPIs)
- Discounted Revenue vs Non-Discounted Revenue
- Discounted Profit vs Non-Discounted Profit
- Profit Margin Difference between the two groups  

---

## 🔹 Data Source and Format
- **Dataset**: [E-Commerce Transactions Dataset (Kaggle – Carrie1)](https://www.kaggle.com/)  
- **Format**: CSV file with transaction-level records  

**Fields include:**  
`Order_Date, Time, Customer_ID, Gender, Device_Type, Product_Category, Product, Sales, Quantity, Discount, Profit, Shipping_Cost, Region, Payment_Method`

Contains both **quantitative fields** (Sales, Profit, Quantity, Discount) and **categorical fields** (Region, Product Category, Customer attributes).  

![Alt text](images/photo1.png)

## 🔹 Key Findings and Business Recommendations

### 1. Strong Profitability
- **2018 Revenue**: ≈ 8M  
- **Profit**: ≈ 3.6M (~46% margin)  
**Recommendation**: Maintain operational efficiency while scaling high-performing product sales.  

### 2. Product & Category Insights
- **Top performers**: Fashion and Home & Furniture  
- **Top products**: T-shirts, watches, running shoes  
- **Underperformers**: Electronics, Auto Accessories  
**Recommendation**: Boost marketing and stock for high-demand products; use promotions/bundles for weaker categories.  

### 3. Seasonality & Demand Trends
- **Observation**: Sales dip in Jan–Feb, rise steadily Mar–May.  
**Recommendation**: Run discount campaigns in Q1 and stock up in late Q2 to capture growth.  

### 4. Discount Insights
- **10–20% discounts** → best revenue & profit.  
- **30–40% discounts** → mainly for expensive items, lower margins.  
**Recommendation**: Focus discounts in the 10–20% range; test reducing discounts on high-ticket items.  

![Alt text](images/photo2.png)

## 🔹 Technologies Used
- **Power BI Desktop** → Data modelling, visualization, dashboard design  
- **Power Query** → Data cleaning and transformation  
- **DAX (Data Analysis Expressions)** → Calculated measures (Revenue, Profit, AOV, Profit Margin %, Discounted vs Non-Discounted Sales)  
- **Excel/CSV** → Input data source  
- **Power BI Maps & Line Charts** → Regional insights and time trend analysis  

