# us-healthcare-data-billing-analysis
Excel-driven Healthcare Data Analytics project analyzing 10,000 patient records. Built using Power Query for data cleaning, multi-dimensional Pivot Tables for aggregation, and dynamic interactive Excel Dashboards with cross-connected Slicers for insights on demographics, admission trends, and financial billing patterns.
# 📊 Healthcare Analytics: Demographics & Financial Billing Dashboard

## 📌 Project Overview
This project delivers an end-to-end data analysis of 10,000 healthcare admission records built entirely in **Microsoft Excel**. The project evaluates patient demographics, disease prevalence across age groups and blood types, admission dynamics, and financial billing burdens across medical conditions.

The workbook is structured into two core problem statements to optimize hospital resource allocation, intake planning, and revenue management.

---

## 🛠️ Excel Architecture & Tools Used
* **Data Cleaning & Transformation:** Utilized **Power Query** to clean raw healthcare data, handle missing values, bucket patient ages, and standardize category text.
* **Data Modeling & Aggregation:** Constructed multi-dimensional **Pivot Tables** to compute patient counts, average billing amounts, and seasonal intake metrics.
* **Interactive Dashboarding:** Built dynamic dashboard views featuring **Pivot Charts**, visual summary KPIs, and cross-connected **Slicers** (*Age Bucket*, *Blood Type*, *Admission Type*) for real-time filtering across all visual components.

---

## 📈 Key Insights & Analysis

### Problem 1: Patient Demographics & Volume Distribution
* **Senior Dominance:** Seniors account for **52.04%** (5,204 cases) of total hospital admissions.
* **Top Condition:** **Hypertension** is the single most prevalent condition, accounting for **21.55%** (2,155 cases) of all admissions.
* **Blood Type Distribution:** Admissions are evenly spread across all 8 blood types (~1,250 cases each), indicating no specific condition-to-blood-type bias.

### Problem 2: Financial Impact & Admission Dynamics
* **Revenue Drivers:** **Cancer** ($39,688.33 avg billing) and **Diabetes** ($30,097.46 avg billing) represent the highest financial load per patient stay.
* **Intake Flow:** **Emergency** visits dominate total patient volume at **35.87%** (3,587 cases) and generate the highest per-stay average billing ($24,289.12).
* **Peak Seasonality:** **October** recorded the highest single-month intake with **883 admissions** (driven by 333 emergency cases).

---

## 📂 Repository Structure
```text
├── Healthcare_Data_project.xlsx   # Full Excel workbook (Cleaned Data, Pivot Tables, & Interactive Dashboards)
└── README.md                       # Detailed project documentation and insights summary
