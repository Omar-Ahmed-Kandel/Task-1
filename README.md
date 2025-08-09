# 📊 Sales Analysis Report

## 🔹 Introduction
This analysis is based on transactional data for a company selling office supplies, furniture, and technology products. The goal is to uncover actionable insights to improve sales strategies, customer engagement, and operational efficiency.

---

## 📚 Table of Contents
1. [Executive Summary](#executive-summary)
2. [Objectives & Key Questions](#objectives--key-questions)
3. [Data Preparation](#data-preparation)
4. [Key Measures & KPIs](#key-measures--kpis)
5. [Insights & Recommendations](#insights--recommendations)
6. [Limitations](#limitations)
7. [Next Steps & Decisions](#next-steps--decisions)
8. [Dashboards](#dashboards)
9. [Dataset](#dataset)

---

## 📜 Executive Summary
The company operates across multiple regions in the United States, selling a diverse range of products. The sales data spans several years and includes customer information, product categories, and shipping details. 

### Key Takeaways:
- Furniture is a high-ticket but lower-frequency category.
- The West and South regions show strong sales activity.
- Segment-wise, *Consumer* customers are the largest contributors to revenue.

---

## 🎯 Objectives & Key Questions
1. Which product categories drive the most sales?
2. Who are our top-performing customers and regions?
3. How does customer segment affect purchasing behavior?
4. What trends can we see across time or shipping methods?

---

## 🛠️ Data Preparation
- **Merged Tables**:
  - `Sales` joined with `DIM Product`, `DIM Customer`, and `DIM Order` on relevant IDs.
- **Data Cleaning**:
  - Dates converted to datetime format.
  - Duplicates and null values checked; dataset is clean.
- **New Columns Created**:
  - `Year` and `Month` from `Order Date` for time analysis.
  - Total sales aggregated per category, segment, and region.

---

## ▶️ Key Measures & KPIs

| KPI | Description |
|-----|-------------|
| **Total Sales** | Sum of all sales across transactions |
| **Average Order Value** | Mean sales value per order |
| **Sales by Category** | Aggregated sales by product category |
| **Sales by Segment** | Total sales by customer type (Consumer, Corporate, Home Office) |
| **Sales by Region** | Regional performance comparison |

---

## 🔍 Insights & Recommendations
- **Top Category**: *Office Supplies* leads in volume, but *Furniture* leads in high-value sales.
- **Segment Insights**: *Consumer* customers make up the majority of sales. Consider targeted campaigns for *Corporate* clients to balance revenue.
- **Shipping Mode**: *Standard Class* is most used. Introducing incentives for faster delivery may attract high-value customers.
- **City-Level Performance**: Cities like *Los Angeles* and *New York* show recurring strong sales—ideal candidates for regional promotions.

### Recommendations:
- Launch targeted promotions in top-performing cities.
- Offer loyalty incentives for high-spending Consumer customers.
- Bundle low-cost Office Supplies to increase Furniture category sales.

---

## ⛔ Limitations
- No cost data—profitability per category or customer could not be measured.
- No return/refund data—customer satisfaction insights are limited.
- Time range appears to be fixed; unclear if latest trends are included.

---

## 🔄 Next Steps & Decisions
- Integrate cost data to perform profit-based analysis.
- Enrich customer data with behavioral/demographic insights for deeper segmentation.
- Monitor monthly performance to catch seasonal trends.

---

## 📊 Dashboards
![Sales Dashboard](https://github.com/Omar-Ahmed-Kandel/Task-1/blob/main/Screenshot%202025-08-02%20170020.png?raw=true)

---

## 📂 Dataset
[**Download Dataset**](https://github.com/Omar-Ahmed-Kandel/Task-1/blob/main/train.csv)
