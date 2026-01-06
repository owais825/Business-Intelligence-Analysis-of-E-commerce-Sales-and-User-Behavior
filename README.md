# Business-Intelligence-Analysis-of-E-commerce-Sales-and-User-Behavior

## 📌 Project Overview

This project analyzes end-to-end e-commerce performance using the **Maven Fuzzy Factory dataset**. The goal is to understand user behavior, conversion funnel efficiency, product profitability, refund impact, and traffic quality through structured data analysis and interactive dashboards.

The project follows a **real-world data analyst workflow**: data cleaning, exploratory analysis, KPI creation, and business-focused visualization.

---

## 🎯 Business Objectives

* Identify **drop-offs in the conversion funnel** from landing to order completion
* Evaluate **product-level revenue, profit, and cross-sell performance**
* Analyze **refund trends and revenue leakage**
* Measure **traffic quality** using revenue per session and device-level conversion rates
* Deliver **executive-ready dashboards** for decision-making

---

## 🗂️ Dataset Description

The analysis is based on six relational CSV tables:

* **website_sessions** – session-level traffic, device, and marketing data
* **website_pageviews** – user navigation paths and funnel steps
* **orders** – completed purchases and order-level revenue
* **order_items** – product-level order details
* **order_item_refunds** – refunded items and amounts
* **products** – product catalog and launch dates

---

## 🧹 Data Preparation

Performed using **Python (Pandas) in Google Colab**:

* Converted timestamp columns to datetime format
* Handled missing values and text-based "null" entries
* Validated primary and foreign key relationships
* Created derived features for funnel and traffic analysis
* Exported clean datasets for Power BI

---

## 📊 Key Analyses

### 1️⃣ Executive KPIs

* Total Revenue
* Total Profit
* Profit Margin
* Total Orders
* Revenue per Session

### 2️⃣ Conversion Funnel Analysis

* Landing → Product → Cart → Shipping → Billing → Order
* Funnel drop-off and stage-wise conversion rates
* Device-level funnel comparison

### 3️⃣ Product Performance

* Revenue, profit, and units sold by product
* Primary vs cross-sell product contribution

### 4️⃣ Refund Analysis

* Refund amount and count by product
* Gross vs net revenue comparison
* Refund trends over time

### 5️⃣ Traffic & Device Analysis

* Sessions by traffic source
* Revenue per session by source
* Conversion rate by device
* Repeat vs new session behavior

---

## 📈 Dashboard Design (Power BI)

The Power BI report contains **five pages**:

1. **Executive Overview** – High-level business health KPIs
2. **Conversion Funnel** – User journey and drop-offs
3. **Product Performance** – Revenue and profit drivers
4. **Refund Analysis** – Revenue leakage insights
5. **Traffic & Device Analysis** – Traffic quality and behavior

Features:

* DAX measures for KPIs and ratios
* Year and device slicers
* Consistent color theme for clarity
* Business-friendly labels and formatting

---

## 🛠️ Tools & Technologies

* **Python** (Pandas, NumPy)
* **Google Colab**
* **Power BI** (DAX, interactive dashboards)
* **CSV-based relational data modeling**

---

## 📌 Key Learnings

* Funnel analysis highlights optimization opportunities beyond total sales
* Traffic volume does not always equal traffic value
* Refund analysis is critical for understanding true revenue performance
* Clean data modeling significantly improves dashboard quality and insight clarity

---

## 📎 How to Use

1. Load raw CSV files into Google Colab
2. Run data cleaning and preprocessing scripts
3. Import cleaned datasets into Power BI
4. Create relationships and DAX measures
5. Build dashboards using provided structure

---

## 👤 Author

**Data Analyst Project** – Built for portfolio and interview demonstration

---

## ⭐ Acknowledgement

Dataset provided by **Maven Analytics (Fuzzy Factor
