# 📊 Sales Data Analysis using Excel

[![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?logo=microsoft-excel&logoColor=white)](#)
[![Project Type](https://img.shields.io/badge/Type-Data%20Analytics%20Dashboard-orange)](#)
[![Status](https://img.shields.io/badge/Status-Completed-success)](#)

> A professional **Excel data analytics dashboard** designed to analyze and visualize sales performance, customer segments, and product trends.  
> This project transforms raw sales data into **business insights** using Excel’s advanced analytics and visualization tools.

---

## 🧭 Overview

**Business Problem:**  
The company needed to understand **sales performance, customer demographics, and product profitability** to support strategic decision-making and growth planning.

**Delivered Solution:**  
A **fully interactive Excel dashboard** featuring pivot charts, KPIs, and slicers that allow users to explore sales performance by region, product, and customer group — all within a clean, professional layout.

---

## 🖼️ Dashboard Preview

Here’s a visual preview of the final dashboard 👇

![Dashboard Preview](Dashboard.png)

---

## 🎯 Key Business Questions

1. What are the overall sales and order trends across months?  
2. Which regions and product categories generate the most revenue?  
3. Who are the main customers by gender and age group?  
4. What are the most profitable products?  
5. How do different regions or sales channels compare in performance?  
6. When did sales peak throughout the year?  
7. What is the order fulfillment and return rate?

---

## 🛠️ Tools & Techniques

| Category | Tools / Techniques |
|-----------|--------------------|
| **Software** | Microsoft Excel 2016 / 365 |
| **Data Cleaning** | Power Query, Text Functions, Data Validation |
| **Analysis** | Pivot Tables, Advanced Excel Formulas (`SUMIFS`, `COUNTIFS`, `INDEX-MATCH`) |
| **Visualization** | Column, Line, Pie, and Bar Charts |
| **Interactivity** | Slicers, Filters, Conditional Formatting |
| **Design** | Corporate-style layout, KPI Cards, Color Consistency |

---

## 📈 Dashboard Highlights

### 🔍 Interactive Filters
- Filter by **Region**, **Category**, **Month**, or **Customer Segment**  
- All visuals dynamically update with slicer selection  

### 💡 Key Performance Indicators (KPIs)
- **Total Revenue:** ₹34.5M  
- **Total Orders:** 21,320  
- **Average Order Value:** ₹1,620  
- **Fulfillment Rate:** 92% Delivered  
- **Top Product Category:** Electronics  
- **Peak Sales Month:** March  

### 📊 Visual Insights
- **Monthly Sales Trend:** Tracks revenue vs. orders  
- **Customer Demographics:** Gender and age-based insights  
- **Regional Breakdown:** Highlights top 5 revenue-generating states  
- **Product Category Analysis:** Shows category contribution to total revenue  
- **Order Status Overview:** Delivered, Cancelled, Returned, Refunded  

---

## 🔎 Insights Summary

1. **Sales Trends:**  
   - Strong Q1–Q2 performance with a **sales peak in March**  
   - Gradual slowdown during the last quarter  

2. **Customer Profile:**  
   - **Women (64%)** dominate purchases  
   - **Adults (25–45 years)** generate most of the revenue  

3. **Regional Insights:**  
   - **Maharashtra** leads in revenue, followed by **Karnataka** and **Uttar Pradesh**  

4. **Product Analysis:**  
   - Electronics and Apparel are top-performing categories  
   - Seasonal demand patterns identified  

5. **Order Fulfillment:**  
   - **92% successful delivery rate** indicates operational efficiency  
   - Low return ratio shows customer satisfaction  

---

## 💼 Business Recommendations

✅ **Focus on Key Customer Segment**  
- Target **women aged 25–45** with customized marketing campaigns  

✅ **Invest in Top Regions**  
- Expand operations and inventory in **Maharashtra** and **Karnataka**  

✅ **Strengthen High-Performing Categories**  
- Increase product visibility and offers on **electronics and fashion items**  

✅ **Plan Seasonal Offers**  
- Launch promotions during high-demand months (March–April)  

✅ **Reduce Return Rate**  
- Improve product quality checks and detailed descriptions  

---

## ⚙️ Technical Implementation

### Data Preparation
- Removed duplicates and blank values  
- Standardized columns and category labels  
- Created calculated fields (Month, Quarter, Age Group)  
- Ensured data consistency for accurate visual reporting  

### Dashboard Design
- Used **corporate color palette** (Blue & Orange)  
- Designed **KPI cards** for clear performance tracking  
- Added **responsive slicers** controlling all visuals  
- Optimized chart spacing and alignment for readability  

---

### Sample Formulas
```excel
Total Sales = SUM(Amount)
Order Fulfillment Rate = Orders_Delivered / Total_Orders
Average Order Value = Total_Sales / Total_Orders
Age Group = IF(Age<20,"Teen",IF(Age<40,"Adult",IF(Age<60,"Middle Age","Senior")))
