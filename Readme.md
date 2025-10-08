# Inventory and Supply Chain Management Analysis

This project analyzes key metrics in **inventory and supply chain management** using **Power BI**. The dashboard and dataset provide actionable insights into warehouse utilization, transportation costs, lead times, inventory turnover, and sales performance across categories and regions.

---

## Dataset
**File:** `Raw dataset.csv`  
**Description:** Transactional and operational data related to inventory, warehouse performance, transportation, and sales.

**Key columns (example):**
- `Region` – Geographical region (North, South, East, West)  
- `Category` – Product category (Clothing, Accessories, Electronics, Furniture)  
- `Units Sold` – Units sold per time period  
- `Transportation Cost` – Logistics cost per record  
- `Warehouse Utilization (%)` – Share of warehouse capacity used  
- `Inventory Level` – Stock level per category/region  
- `Lead Time (Days)` – Replenishment lead time  
- `Backorder Status` – Order fulfillment state (Fulfilled, Pending, Canceled)

---

## Power BI Dashboard Overview

The dashboard visualizes the following key components:

- **Warehouse Utilization** — Gauge showing current utilization vs. target (e.g., 75%).  
- **Transportation Cost by Region and Category** — Clustered bar chart comparing logistics costs across regions & categories.  
- **Units Sold by Year** — Line/area chart showing sales trend (2020–2024).  
- **Average Lead Time (Days) by Category** — Donut/pie chart showing mean lead time for each category.  
- **Count of Backorder by Order Status** — Bar chart counting fulfilled, pending, and canceled backorders.  
- **Inventory Level by Category and Region** — Horizontal bar chart comparing inventory across regions and categories.

---

## Key Metrics (from dashboard)
- **Warehouse Utilization:** `34.08%`  
- **Day Sales of Inventory:** `15.56` days  
- **Inventory Turnover Ratio:** `23.47`

> These KPIs indicate overall inventory efficiency and highlight capacity and supply chain cost issues.

---

## Insights & Observations
- Warehouse utilization is well below the target — potential opportunity to consolidate or expand utilization strategies.  
- Transportation costs peak in the **West** region, particularly for **Furniture** and **Electronics**.  
- Sales (units sold) show a significant increase after 2021, which may coincide with demand changes or improved distribution.  
- Accessories have the highest average lead time, suggesting supplier or replenishment constraints.  
- Most orders are fulfilled (`838`), but pending and canceled backorders exist and warrant further investigation.

### 🧠 Insights Summary
The dashboard highlights **strong sales recovery and efficient inventory turnover**, but **underused warehouse capacity (34%)** and **high transportation costs in the West region** indicate optimization opportunities in logistics and storage utilization.

---

## Tools & Techniques
- **Power BI** — Visualizations and dashboarding  
- **Power Query & DAX** — Data transformations and KPI calculations  
- **CSV / Excel** — Data storage and pre-processing

---
