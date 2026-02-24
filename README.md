# OptiStock – Supply Chain & Inventory Optimization Dashboard

**Author:** Anne Anita Beaula P

---

## 🔎 Project Overview

OptiStock is a Power BI dashboard designed to solve real-world inventory management challenges in a retail supply chain environment.

Retail businesses often face:
- 🚫 Frequent stockouts of high-demand products
- 📦 Overstocking of slow-moving items
- 💰 Capital locked in excess inventory
- 📉 No visibility into future demand

This dashboard provides a centralized, interactive solution to monitor inventory health and forecast demand.

---

## 🎯 Business Objective

To help Supply Chain Managers:
- Identify stockout risks early
- Detect overstocked products
- Optimize reorder decisions
- Improve inventory efficiency
- Forecast demand trends

---

## 🏗 Data Model

Implemented an optimized Star Schema.

**Fact Tables:**
- fSales
- fInventorySnapshots
- fPurchaseOrders

**Dimension Tables:**
- dProduct
- dSupplier
- dWarehouse
- dDate

Relationships were configured to ensure accurate filtering and performance optimization.

---

## 📊 Core DAX Measures

Key business metrics implemented:
- Inventory Value
- Stock Turn
- Sell-Through Rate %
- Days on Hand
- On-Time Delivery %
- Stockouts

Advanced DAX concepts used:
- Time intelligence
- Ratio calculations
- Inventory efficiency logic
- ABC product classification
- Forecast modeling

---

## 📄 Dashboard Pages

### 📍 Page 1 – Inventory Overview
**KPIs Displayed:**
- Total Inventory Value
- Stock Turn
- Sell-Through Rate %
- On-Time Delivery %
- Stockouts

**Visualizations:**
- Inventory Value by Warehouse (Map)
- Top 10 Products by Stock Value (Bar Chart)
- Inventory Performance Over Time (Line Chart)

---

### 📍 Page 2 – Inventory Health
**Analysis Performed:**
- ABC Analysis (A / B / C product segmentation)
- Days on Hand by Product
- Stockout vs Overstock (Scatter Plot)

**Business Value:**
- Identifies high-demand products at risk
- Detects excess inventory in slow-moving products
- Enables smarter inventory balancing

---

### 📍 Page 3 – Demand Forecast
**Visualization:**
- Sales by Month (Line Chart with Power BI Forecast enabled)

**Purpose:**
- Predict future demand
- Plan replenishment
- Reduce uncertainty in procurement

---

## 🔐 Security Implementation

To simulate real-world enterprise security:
- Implemented Row-Level Security (RLS) using WarehouseID
- Hidden sensitive financial columns in the data model
- Simulated role-based access control

---

## 🛠 Tools & Technologies
- Power BI Desktop
- Power Query
- DAX
- Star Schema Data Modeling
- Forecasting Analytics

---

## 📈 Key Business Impact

✔ Reduced stockout risk  
✔ Improved inventory turnover  
✔ Minimized overstocking  
✔ Enabled data-driven supply decisions  
✔ Forecasted demand trends

---

