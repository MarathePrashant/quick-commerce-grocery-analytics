# 🛒 Blinkit Retail Sales & Business Intelligence Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

## 📌 Business Overview & Problem Statement
Blinkit (India's leading quick-commerce network) processes thousands of daily grocery transactions across varied store footprints. The objective of this project was to perform end-to-end data analysis—extracting, transforming, and modeling raw retail data to identify revenue bottlenecks, measure outlet tier profitability, and analyze customer satisfaction metrics.

The resulting interactive Power BI dashboard delivers actionable commercial insights across **$1.20M in Total Revenue** and **8,523 inventory line items**.

---

## 🛠️ Data Architecture & Tech Stack
* **Business Intelligence & Visualization:** Power BI Desktop (DAX, Data Modeling, Visual Hierarchy)
* **Data Processing & ETL:** Power Query (Data Cleansing, Deduplication, Standardization, Custom Columns)
* **Exploratory Data Analysis (EDA):** Microsoft Excel (PivotTables, Parametric Checks)
* **Data Model Architecture:** Star Schema (Fact Sales with Dimension Tables)

---

## 📈 Key Metrics & DAX Formulas

### Custom DAX Measures:
* **Total Sales:** `Total Sales = SUM('BlinkIT Data'[Sales])` → **$1.20M**
* **Average Sales:** `Avg Sales = AVERAGE('BlinkIT Data'[Sales])` → **$140.99**
* **Item Count:** `No of Items = COUNT('BlinkIT Data'[Item Identifier])` → **8,523**
* **Average Rating:** `Avg Rating = AVERAGE('BlinkIT Data'[Rating])` → **3.97 / 5.0**

---

## 💡 Executive Insights & Data Findings

1. **Channel Revenue Breakdown (Outlet Type):**
   * **Supermarket Type 1** is the dominant channel, contributing **$787.55K** (~65.5% of total revenue) across 5,577 sold items.
   * **Grocery Stores** generate **$151.94K** with the highest product visibility ratio (10.5%).

2. **Geographical Performance (Location Tier):**
   * **Tier 3 cities** generated the highest sales volume (**$472.13K** / 39.3%), outperforming Tier 2 (**$393.15K**) and Tier 1 (**$336.40K**) markets.

3. **Store Size Efficiency:**
   * **Medium-sized Outlets** yield the highest revenue output (**$507.90K**), outperforming Small (**$444.79K**) and High-capacity stores (**$248.99K**).

4. **Product Portfolio Distribution:**
   * **Low Fat products** represent **64.6%** ($776.3K) of consumer demand versus Regular Fat items ($425.4K).
   * **Fruits/Vegetables ($178K)** and **Snack Foods ($175K)** lead overall revenue by product category.

---

## 🎯 Business Recommendations
* **Inventory Allocation:** Expand stock capacity for Low-Fat items in Tier 3 locations to match regional consumer demand.
* **Store Footprint Optimization:** Prioritize Medium-sized outlet formats for new store openings due to optimal sales-to-capacity metrics.
* **Visibility Enhancement:** Leverage high product-visibility strategies used in Grocery Stores across Supermarket formats to lift cross-selling.

---

## 📂 Repository Structure
```text
├── Data/
│   └── BlinkIT Grocery Data.xlsx       # Primary Raw Dataset
├── Dashboard/
│   └── Blinkit_Sales_Dashboard.pbix    # Interactive Power BI File
├── Documentation/
│   └── Dashboard_Preview.png           # High-Res Screenshot
└── README.md                           # Project Documentation
