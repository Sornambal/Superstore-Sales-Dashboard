# 🛍️ Superstore Sales Dashboard – Mini Project

This mini project explores retail sales data using **Excel** and **Power BI** to gain business insights. The dataset is based on Superstore sales from [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final).

## 📌 Objectives
- Practice Excel data cleaning
- Build a multi-page interactive dashboard using Power BI
- Analyze customer behavior, product performance, shipping trends, and discount impacts

## 🧹 Data Cleaning in Excel

Steps taken:
1. **Handled missing values** (e.g., no nulls in key columns like `Sales`, `Profit`)
2. **Removed duplicates** in `Order ID` if any
3. Checked for **incorrect data types** (dates, numeric fields)
4. Verified consistent **date formatting**
5. Ensured categorical fields (e.g., Region, Segment) were standardized
6. Removed unused/unnecessary columns for clean import into Power BI

## 📊 Power BI Dashboard – 4 Pages

1. **Page 1: Sales Overview**
   - KPIs: Total Sales, Profit, Orders
   - Charts: Line chart (time-series), Bar (Top categories), Card visuals

2. **Page 2: Product & Category Insights**
   - Matrix (Category > Sub-Category)
   - Top sub-categories by sales
   - Profit trend by category

3. **Page 3: Customer & Shipping Insights**
   - Segment-wise sales (donut chart)
   - Top 10 customers (table)
   - Ship mode performance (bar & pie)
   - Delivery time analysis

4. **Page 4: Geography & Discount Impact**
   - Filled Map (Sales by State)
   - Bar (Profit by State)
   - Scatter plot (Discount vs Profit)
   - Profit distribution (histogram)

## 📌 Patterns & Features Observed

- 📈 Most sales come from the **Consumer** segment
- 🗺️ **California** and **New York** are the top revenue-generating states
- 📉 High discounts often lead to **negative profit**
- 🚛 **Standard Class** is the most used shipping mode
- 📦 **Chairs** and **Phones** are among top-performing sub-categories
- 📉 Some states show consistent **loss despite high sales**, signaling inefficiency

## 📁 Files
- `Superstore Project.pbix`: Full Power BI dashboard
- `Superstore Data.xlsx`: Cleaned dataset
- `README.md`: Project documentation

---


