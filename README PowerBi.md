# powerbi-dax-sales-analysis
Power BI sales report built with advanced DAX measures, Star Schema modeling, and dynamic KPI calculations.

# 📊 Power BI Sales Analysis — DAX & Data Modeling Project

A Power BI report demonstrating advanced **DAX measures**, **data modeling**, and **interactive visualizations** built as part of the DEBI Business Analytics Pre-Master program.

---

## 🎯 Project Overview

This project showcases the use of **Power BI Desktop** and **DAX (Data Analysis Expressions)** to build dynamic, calculated metrics on top of a structured data model — going beyond basic drag-and-drop reporting.

---

## 🧠 DAX Concepts Applied

| Concept | Description |
|---|---|
| **Explicit Measures** | Custom KPIs defined with DAX instead of implicit aggregations |
| **SELECTEDVALUE()** | Dynamic labels and context-aware calculations |
| **SWITCH(TRUE())** | Conditional logic for classification and banding |
| **DAX Variables** | `VAR` / `RETURN` pattern for cleaner, optimized expressions |
| **CALCULATE()** | Context modification for filtered aggregations |
| **Time Intelligence** | Period-over-period comparisons |

---

## 🗂️ Data Model

The report is built on a **Star Schema** design:

```
        Fact Table
       ┌───────────┐
       │   Sales   │
       └─────┬─────┘
    ┌────────┼────────┐
    ▼        ▼        ▼
 Dim Date  Dim Product  Dim Customer
```

- ✅ Proper relationships between fact and dimension tables
- ✅ Single direction filtering for performance
- ✅ Calculated columns separated from measures

---

## ✨ Report Features

- ✅ KPI cards with dynamic DAX measures
- ✅ Year-over-year and month-over-month comparisons
- ✅ Slicers and cross-filtering across visuals
- ✅ Clean, business-ready layout
- ✅ Optimized DAX using variables to avoid redundant calculations

---

## 🛠️ Tools Used

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

- **Power BI Desktop** — Report building & data modeling
- **DAX** — Measure logic and calculations
- **Power Query (M)** — Data transformation and loading

---

## 📸 How to View

> ⚠️ This file requires **Power BI Desktop** (free download from Microsoft).

1. Download `dax.pbix`
2. Open with **Power BI Desktop**
3. Explore the report pages and the **Data Model** tab
4. Open **Model view** to inspect relationships
5. Go to **Report view → Fields pane** to browse DAX measures

🔗 [Download Power BI Desktop](https://powerbi.microsoft.com/desktop/)

---

## 📚 Learning Context

This project was built as part of coursework covering:
- Explicit vs implicit measures in Power BI
- Star and snowflake schema design
- Advanced DAX patterns for real-world reporting
- Excel CUBE functions (CUBEMEMBER, CUBEVALUE) connected to Power BI models

---

## 👤 Author

**Zeyad Emam Mostafa**
📍 Cairo, Egypt
🔗 [LinkedIn](https://www.linkedin.com/in/zeyademam) | 🐙 [GitHub](https://github.com/zeyademam2000)

---

*Part of my Data & Business Analytics portfolio — built during the DEBI Business Analytics Pre-Master program.*
