# 👟 Adidas US Sales Analysis (Interactive Excel Dashboard)

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📄 Executive Summary
This project involves a comprehensive analysis of **Adidas US sales data** to identify the primary drivers of profitability. By processing **~9,000 sales records**, I developed an interactive Excel dashboard that helps stakeholders visualize performance across different regions, retailers, and product categories. The analysis reveals a massive **324% year-over-year growth** in operating profit from 2020 to 2021.

## 📂 Repository Contents
* **`Adidas-US-Interactive-Sales-Project - Abdelrahman.xlsx`**: The complete Excel workbook containing the raw data, pivot tables, and the interactive dashboard.
* **`Screenshot 2026-02-03 014201.png`**: A preview of the final dashboard view.

---

## 🔍 Business Problem
The goal was to analyze historical sales data to optimize future sales strategies. Key business questions included:
1. Which **Sales Method** (In-store vs. Online vs. Outlet) generates the highest margin?
2. Which **Product Categories** are the most profitable?
3. Who are the top-performing **Retailers** and **Regions**?
4. What is the sales trend over time (2020 vs. 2021)?

---

## 💡 Key Insights & Findings
*(Derived directly from the project data)*

* **Explosive Growth:** Operating profit surged from **$63M in 2020** to **$268M in 2021**, indicating a highly successful expansion period.
* **Top Sales Channel:** **In-store sales** remain the dominant revenue driver, generating **$127M** in profit, followed closely by Outlet sales ($107M). Online sales lag slightly behind at $96M.
* **Regional Dominance:** The **West Region** is the most profitable market (**$89.6M**), outperforming the Northeast ($68M) and Midwest ($52M).
* **Retailer Performance:** **West Gear** is the top-performing retailer with **$85.6M** in profit, narrowly beating **Foot Locker** ($80.7M). **Amazon** generated the lowest profit among major partners ($28.8M).
* **Product Strategy:** **"Men's Street Footwear"** is the most lucrative category (**$82.8M** Profit), whereas athletic footwear and apparel contribute significantly less.

---

## 🛠️ Technical Solution & Methodology

### 1. Data Cleaning & Preparation
* **Data Source:** Imported raw CSV sales data containing Retailer, Region, Product, and Transaction details.
* **Normalization:** Standardized text formats for "City" and "Retailer" columns to ensure accurate aggregation.
* **Calculated Fields:** Created custom columns for `Operating Margin` to track efficiency per transaction.

### 2. Analysis (Pivot Tables)
* Utilized Pivot Tables to aggregate millions of dollars in sales data dynamically.
* **Time Intelligence:** Grouped transactional data by **Years (2020, 2021)** and **Quarters** to visualize the steep growth curve.
* **Cross-Tabulation:** Analyzed `Retailer` performance against `Region` to identify coverage gaps.

### 3. Dashboard Implementation
* Built a dynamic **Executive Dashboard** featuring:
    * **Slicers:** allowing users to filter by *Region*, *Year*, and *Product Category* instantly.
    * **Charts:** Trends over time (Line Charts) and Category breakdowns (Donut/Bar Charts).
    * **Conditional Formatting:** Highlighted top and bottom performers automatically.

---

## 🚀 How to Use
1. Download the file **`Adidas-US-Interactive-Sales-Project - Abdelrahman.xlsx`**.
2. Open it in **Microsoft Excel**.
3. Navigate to the **"Dashboard"** sheet (or Sheet 1).
4. Use the **Slicers** (Buttons) to filter the data.

---
*Author: Abdelrahman Hosam*
