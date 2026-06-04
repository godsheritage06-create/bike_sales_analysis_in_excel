# bike_sales_analysis_in_excel
# Bike Buyers Demographics & Sales Performance Dashboard

## 📌 Project Overview
This data analytics project focuses on transforming raw customer data into an interactive business intelligence solution. By analyzing key demographic factors such as income, age, commute distance, and geographic region—this project identifies the primary drivers behind bicycle purchasing behavior. 

The final dynamic dashboard empowers marketing and sales teams to filter customer segments on the fly, uncovering localized trends to optimize targeted ad campaigns.

---

## 🛠️ Data Architecture & Pipeline

The project was executed entirely within Excel across a structured four-stage pipeline:

### 1. Data Cleaning (`Cleaned Dataset`)
* **Deduplication:** Identified and removed duplicate records to establish a unique row per customer profile.
* **Data Standardization:** Normalized abbreviated fields to ensure clarity and reporting consistency.
* **Feature Engineering:** Implemented logical formulas to bin continuous age data into a new categorical metric: `Age Bracket` (*Adolescent, Middle aged, Old*).

### 2. Data Transformation (`pivot table`)
* Aggregated high-dimensional customer data into multi-variable summary tables.
* Computed specific operational metrics, including *Average Income per Purchase* grouped by gender and purchase intent, alongside *Customer Commute* distribution counts.

### 3. Dynamic Visualization (`dashboard`)
* Designed a clean visual interface utilizing synchronized bar and line charts to contrast buyer vs. non-buyer attributes.
* Embedded responsive **Slicers** (*Marital Status, Region, Education, Age Bracket*) allowing stakeholders to perform cross-sectional analysis dynamically.

---

## 📈 Key Insights Discovered

* **The Income Threshold:** Customers who successfully purchased a bicycle exhibited a noticeably higher average income bracket across both male and female demographics compared to non-buyers.
* **The Demographics Sweet Spot:** The engineered `Middle aged` bracket holds the overwhelming majority of bike purchases, marking them as the primary target segment for high-tier marketing campaigns.
* **The Commute Factor:** Purchasing intent peaks sharply for customers living within a **0–1 mile** radius of their commute. A direct inverse relationship occurs as distance grows: willingness to buy drops drastically once a commute exceeds **2–5 miles**.

---

## 📂 File Reference Guide

To review the structural development of the workbook, refer to the following sheets in the project file:
* **`bike_buyers Dataset`**: The raw, unformatted data repository before structural processing.
* **`Cleaned Dataset`**: The sanitized operational dataset used for downstream analysis.
* **`pivot table`**: The back-end data aggregation layers driving the charts.
* **`dashboard`**: The front-end, stakeholder-facing interactive report interface.

---

## 🚀 How to Interact with the Dashboard
1. Download the `Excel Project Dataset.xlsx` file from this repository.
2. Open the file in Microsoft Excel (ensure editing/macros are enabled if prompted).
3. Navigate to the **`dashboard`** tab.
4. Use the custom panel buttons on the left-hand side to instantly filter all visual graphs by specific customer demographics.
