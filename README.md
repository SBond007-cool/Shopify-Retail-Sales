# 🛒 Shopify Data Analysis – Power BI Dashboard Project (2025)

This repository presents a **Power BI project** focused on analyzing **Shopify sales data** to generate actionable
insights into customer behavior, transaction performance, product trends, and regional performance.

---

## 📦 Project Overview

This project demonstrates how Power BI can be used to analyze e-commerce performance using real-world Shopify sales data.
It focuses on customer segmentation, sales metrics, payment gateway trends, and time-based ordering behavior, 
enabling data-driven decision-making for online retail businesses.

---

## 🗂️ Data Source

A one week Shopify store dataset including:
- Order-level data
- Customer and product information
- Shipping location details
- Payment gateway methods


## 📊 Key Performance Indicators (KPIs)

### 🔁 Transaction Performance
- **Net Sales**: `$4,180,874`
- **Total Customers**: `4,431`
- **Total Quantity Sold**: `7534`
- **Net Average Order Value (AOV)**:  `$562.6`
### 👤 Customer Purchase Behavior
- **Repeat Order Customers**: `2,039`
- **Repeat Rate**: `46.02%`
- **Multiple Order Customers**:  `2039`
### 💳 Payment Trends
- **Top Payment Method**: Shopify Payments (`58%`), PayPal (`17%`)
- **Shopify Payments** (overall including all methods): `~80%` usage

---

## 🧠 Key Insights

- 📌 **High repeat rate**  `46.02%` indicates strong customer loyalty and retention potential.
- 🕒 **Peak ordering time**: Between **9 AM – 3 PM**.
- 🌎 **Top Provinces by Sales**:
  1. Washington  
  2. Las Vegas  
  3. Houston  
  4. Pietasberg

- 🏙 **Top 5 Cities by Revenue**:
  1. Washington  
  2. Houston  
  3. New York  
  4. El Paso  
  5. Dallas

- 👟 **Best-Selling Products**: Running Shoes, Tennis Shoes

---

## 📐 Dashboard Design

### 1️⃣ Main Dashboard
- Metric Selector: Toggle between Net Sales, Quantity, Repeat Customers, etc.
- **Province-level Fill Map** for regional analysis
- **City-level Bubble Map** for order volume density
- **Bar Charts**:
  - Sales trend by hour and day
  - Top-performing cities and products
- **Donut Chart**: Payment gateway distribution
- **Column Chart**: Product category performance

### 2️⃣ Details Dashboard
- Drill-through-enabled detailed order-level table
- Filters available for:
  - Payment Method
  - Province
  - Customer Type (Repeat vs. First-Time)

---

## 🧱 Data Modeling

- Single-table model for quick implementation
- Minimal transformation required in Power Query
- DAX measures created for all KPIs and calculated segments
- Dynamic visuals powered by slicers and parameters

---

## 🧠 Skills Demonstrated

- Power BI dashboard development
- Advanced DAX for KPIs (AOV, Repeat Rate, Sales Metrics)
- Drill-through and interactivity design
- E-commerce analytics and customer segmentation
- Visual storytelling and business insight extraction

---

## 📂 Repository Structure
