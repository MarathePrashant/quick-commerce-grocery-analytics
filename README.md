# 🛒 Quick-Commerce Grocery Sales Analytics

> **Interactive Power BI analytics project analyzing $1.20M in grocery sales across 8,500+ items to evaluate product performance, outlet efficiency, customer-facing visibility, and sales opportunities.**

## 📌 Business Problem

Quick-commerce and grocery businesses need to continuously optimize:

* Product assortment
* Inventory allocation
* Outlet performance
* Product visibility
* Store footprint
* Category-level sales

This project analyzes grocery sales data to identify the product and outlet characteristics that influence sales performance and to convert those findings into actionable retail recommendations.

---

## 🎯 Project Objectives

The analysis focuses on:

1. **Sales Performance** — identify high-performing products and categories.
2. **Outlet Analytics** — compare sales across outlet tiers and outlet sizes.
3. **Product Analytics** — understand item characteristics and visibility.
4. **Revenue Efficiency** — evaluate sales productivity across different outlet formats.
5. **Business Intelligence** — build an interactive Power BI dashboard for decision-making.

---

## 📊 Project Snapshot

| Metric           |           Value |
| ---------------- | --------------: |
| Total Sales      |      **$1.20M** |
| Items Analyzed   |      **8,500+** |
| BI Tool          |    **Power BI** |
| Data Preparation | **Power Query** |
| Calculations     |         **DAX** |
| Data Modeling    | **Star Schema** |

---

## 🛠️ Tech Stack

| Area                  | Tools                   |
| --------------------- | ----------------------- |
| Business Intelligence | Power BI                |
| ETL                   | Power Query             |
| Calculations          | DAX                     |
| Data Modeling         | Star Schema             |
| Source Data           | Excel                   |
| Visualization         | Power BI                |
| Analytics             | Retail / FMCG Analytics |

---

## 🔄 End-to-End BI Workflow

```text
Raw Grocery Sales Data
        ↓
Power Query ETL
        ↓
Data Cleaning & Transformation
        ↓
Data Modeling
        ↓
Star Schema
        ↓
DAX Measures
        ↓
Interactive Power BI Dashboard
        ↓
Business Insights
        ↓
Retail Recommendations
```

---

## 🧹 Data Preparation

Power Query was used to prepare the dataset for analysis by:

* Handling missing outlet attributes
* Standardizing product and category fields
* Transforming numerical fields
* Preparing analysis-ready dimensions
* Validating data types
* Creating a structured analytical model

---

## 🏗️ Data Model

The Power BI solution uses a **star-schema approach** to separate transactional sales information from descriptive product and outlet attributes.

Conceptually:

```text
                 Product Dimension
                        │
                        │
                        ▼
              ┌──────────────────┐
              │   Sales Facts    │
              └──────────────────┘
                        ▲
                        │
                        │
                  Outlet Dimension
```

This structure supports efficient filtering, aggregation, and DAX-based KPI analysis.

---

## 📈 Key KPIs

The dashboard includes business-focused measures such as:

* **Total Sales**
* **Average Sales per Item**
* **Item Visibility vs Revenue Efficiency**
* **Outlet Performance**
* **Product Category Performance**
* **Outlet Tier Performance**
* **Outlet Size Performance**

---

## 🔍 Key Business Questions

### Product Performance

* Which product categories generate the highest sales?
* Which product attributes are associated with stronger performance?
* Which products demonstrate low sales velocity?

### Outlet Performance

* Which outlet tiers generate the most revenue?
* Does larger outlet size always produce higher sales?
* Which outlet formats provide stronger revenue productivity?

### Product Visibility

* How does item visibility relate to sales?
* Can visibility metrics support better assortment and shelf-space decisions?

---

## 💡 Key Business Insights

### 1. Outlet Tier Performance

**Tier-3 outlets contributed the largest share of revenue** in the analyzed dataset.

**Business implication:**
Smaller geographic markets can represent significant revenue opportunities and should not be overlooked in expansion and assortment strategies.

### 2. Product Attribute Performance

Low-fat and health-oriented product segments demonstrated strong sales contribution.

**Business implication:**
Product attributes can be incorporated into assortment planning and category strategy.

### 3. Outlet Size Efficiency

Larger outlets did not consistently generate proportionally higher revenue than medium-sized outlets.

**Business implication:**
Outlet footprint should be evaluated against revenue productivity rather than assuming that larger stores always perform better.

### 4. Product Visibility

Item visibility showed useful relationships with sales performance.

**Business implication:**
Visibility metrics can support more informed decisions around assortment, shelf space, and product placement.

---

## 💼 Business Recommendations

### 🔹 Optimize Product Assortment

Prioritize high-performing and fast-moving FMCG categories when planning inventory for high-potential outlets.

### 🔹 Evaluate Outlet Footprint

Compare outlet size against revenue productivity before expanding physical footprints.

### 🔹 Reallocate Low-Velocity Inventory

Identify consistently underperforming products and redirect inventory capacity toward higher-performing categories.

### 🔹 Improve Visibility-Based Decisions

Combine product visibility, sales performance, category, and outlet information to improve assortment planning.

### 🔹 Build Data-Driven Replenishment Rules

Use historical sales performance and outlet characteristics to support more targeted inventory allocation and replenishment decisions.

---

## 📊 Power BI Dashboard

The interactive dashboard provides views for:

* Executive sales KPIs
* Product/category performance
* Outlet performance
* Outlet tier comparison
* Outlet size analysis
* Product visibility
* Revenue efficiency

**Power BI file:** `Blinkit.pbix`

---

## 🧠 Skills Demonstrated

* Power BI
* Power Query
* DAX
* Star Schema Data Modeling
* KPI Development
* Retail Analytics
* FMCG Analytics
* Sales Analysis
* Product Performance Analysis
* Outlet Performance Analysis
* Data Visualization
* Business Intelligence
* Business Storytelling

---

## 📂 Project Structure

```text
quick-commerce-grocery-analytics/
│
├── data/
│   └── BlinkIT_Grocery_Data.xlsx
│
├── powerbi/
│   └── Blinkit.pbix
│
├── screenshots/
│   ├── dashboard-overview.png
│   ├── sales-analysis.png
│   ├── outlet-analysis.png
│   └── product-analysis.png
│
└── README.md
```

> **Important:** Create these folders and move the existing files before using this structure in the README.

---

## 🚀 Business Value

This project demonstrates how a raw Excel dataset can be transformed into an interactive BI solution that helps retail and quick-commerce teams:

* Understand sales performance
* Identify high-performing categories
* Compare outlet productivity
* Optimize product assortment
* Improve inventory allocation
* Evaluate outlet expansion opportunities
* Support data-driven retail decisions

---

## 👤 Author

**Prashant Marathe**

B.Tech — Artificial Intelligence & Data Science

**Target Roles:** Data Analyst | BI Analyst | Business Analyst

📍 Pune, Maharashtra, India

* [LinkedIn](https://www.linkedin.com/in/prashantmarathe17)
* [Portfolio](https://prashant-marathe.framer.website/)
* [GitHub](https://github.com/MarathePrashant)
* Email: [p04747391@gmail.com](mailto:p04747391@gmail.com)
