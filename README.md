# 🛒 Blinkit Grocery Quick-Commerce Sales Analytics

[![Power BI](https://img.shields.io/badge/Power_BI-Executive_Dashboard-F2C811?style=flat-square\&logo=powerbi)](#)
[![DAX](https://img.shields.io/badge/DAX-Advanced_Measures-0055FF?style=flat-square)](#)
[![Data Modeling](https://img.shields.io/badge/Model-Star_Schema-green?style=flat-square)](#)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)](#)

## 📌 Executive Summary & Business Problem

Quick-commerce retail depends on efficient inventory movement, optimized product assortment, and effective micro-fulfillment operations.

This project analyzes **$1.20M in total sales** across **8,500+ grocery items** to evaluate how outlet characteristics, geographic tiers, product attributes, and item visibility influence sales performance and store-level efficiency.

## 🛠️ Data Pipeline & Technical Approach

* **Power Query ETL:** Standardized inconsistent category and product attributes, handled missing outlet-size values, and transformed numerical fields into analysis-ready formats.
* **Data Modeling:** Designed a structured **star-schema data model** connecting grocery sales facts with item and outlet dimensions.
* **DAX KPI Development:** Created business-focused measures including:

  * `Total Sales ($)`
  * `Average Sales Per Item`
  * `Item Visibility vs. Revenue Efficiency`
  * `Outlet Footprint Performance`
* **Dashboard Development:** Built an interactive Power BI dashboard with KPIs, category analysis, outlet comparisons, and business-performance visualizations.

## 📂 Project Structure

```text id="c7yq4h"
├── assets/             # Dashboard previews and report visuals
├── data/               # Raw and cleaned grocery sales datasets
├── dashboards/         # Power BI project file (.pbix)
└── README.md           # Business case study, methodology, and findings
```

## 📊 Key Business Insights

* **Outlet Tier Performance:** Tier-3 outlets contributed the largest share of revenue in the analyzed dataset, highlighting strong sales potential across smaller geographic markets.
* **Product Attribute Performance:** Low-fat and health-oriented product segments demonstrated strong sales contribution, indicating opportunities for targeted assortment planning.
* **Outlet Size Efficiency:** Larger outlets did not consistently generate proportionally higher revenue than medium-sized outlets, suggesting that outlet footprint should be evaluated alongside revenue productivity.
* **Product Visibility:** Item visibility and sales performance showed useful relationships that can support more informed shelf-space and assortment decisions.

## 💡 Strategic Business Recommendations

* **Assortment Optimization:** Prioritize high-performing and fast-moving FMCG categories when planning inventory for high-potential outlets.
* **Outlet Footprint Optimization:** Evaluate medium-sized outlet formats as a potentially more capital-efficient model where they deliver comparable sales performance with a smaller physical footprint.
* **Low-Velocity Reallocation:** Reallocate space and inventory from consistently underperforming products toward higher-velocity categories based on sales contribution.
* **Data-Driven Inventory Planning:** Combine sales performance, outlet tier, product characteristics, and visibility metrics to improve SKU-level assortment and replenishment decisions.

## 🚀 How to Explore This Project

1. **Open the Dashboard:** Download `/dashboards/blinkit_sales_dashboard.pbix` and open it in **Power BI Desktop** to interact with the dashboard, filters, slicers, and KPI cards.
2. **Review Data Transformations:** Open **Power Query** within the report to examine the ETL workflow, cleaning steps, and data transformations.
3. **Review the Data Model:** Inspect the Power BI model to understand the star-schema structure and relationships between sales, item, and outlet data.
4. **Review DAX Measures:** Explore the DAX calculations used to create the project's business KPIs.

## 👤 Author

**Prashant Marathe**

* **LinkedIn:** https://www.linkedin.com/in/prashantmarathe17
* **Portfolio:** https://prashant-marathe.framer.website/
* **Email:** [p04747391@gmail.com](mailto:p04747391@gmail.com)
* **Location:** Pune, Maharashtra, India
