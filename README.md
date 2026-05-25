# Commercial Sales Performance Dashboard (Tableau)

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-007ACC?style=for-the-badge)

## 📊 Project Overview
This repository contains an Interactive Commercial Sales Performance Dashboard developed in Tableau. The primary objective of this project is to provide the sales management team with a dynamic, visual tool to track revenue goals, evaluate the lead conversion funnel, and segment performance by product category (fencing materials).

The analytics framework is built to answer critical business questions, such as:
* Which sales representatives are meeting or exceeding their yearly targets?
* What is the financial impact of lost opportunities compared to won deals (`ClosedWon`)?
* Which materials drive the highest percentage of company revenue?

---

## 🎯 Key Dashboard Features
* **Dynamic Simulation Parameters:** Configured adjustable sales targets (`Sales Target`) to enable what-if scenarios and dynamic commercial planning.
* **Advanced KPI Indicators:** Leveraged calculated fields and conditional logic with visual alerts (`▲` / `▼`) to instantly highlight performance variances against goals.
* **Interactive Data Exploration:** Implemented highlight actions and cross-filtering by product category (`Fence Type`) for deep-dive granular analysis without cluttering the user interface.
* **Pipeline Status Segmentation:** Structured data filtering based on corporate business logic (e.g., isolating the `ClosedWon` state for accurate revenue tracking).

---

## 🛠️ Tech Stack & Tools
* **Data Visualization:** Tableau Desktop (Version 2026.1).
* **Data Source:** A structured Excel dataset (`datos_aleatorios.xlsx`) containing transaction histories, material categories, sales representatives, and sales pipeline stages.
* **Canvas Layout:** Organized utilizing object containers to ensure a clean, modern, corporate, and responsive interface layout.

---

## 📂 Repository Structure
* `/data`: (Optional) Sample anonymized or mock dataset used for the dashboard.
* `SALES_FINAL.twbx`: The packaged Tableau workbook containing the dashboard design, sheets, and embedded data for local viewing.
* `README.md`: Project documentation and presentation.

---

## 🚀 How to View the Dashboard

### Option 1: Tableau Public (Recommended)
You can interact with the fully dynamic, live version of this dashboard online through my Tableau Public profile:
👉 (https://public.tableau.com/app/profile/viviana.bedoya/viz/FenceSalesTablauDashboard/Dashboard2)

### Option 2: Local Desktop View
To explore the technical architecture, custom calculated fields, and backend parameters:
1. Clone this repository to your local machine.
2. Ensure you have **Tableau Desktop** or **Tableau Reader** installed.
3. Open the `SALES_FINAL.twbx` file.

---

## 💡 Key Design & Data Decisions
* **Data Quality & Wrangling:** Identified and normalized minor source-data inconsistencies during development (such as standardizing misspelled categories like `"Aluminumn"` to its correct format).
* **KPI Hierarchy:** Prioritized a top-down reading flow (left to right) to present macro-level corporate KPIs clearly before descending into vendor and product-specific breakdowns.
