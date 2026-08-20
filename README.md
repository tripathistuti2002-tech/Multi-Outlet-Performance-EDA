# Multi-Outlet Performance EDA

An Exploratory Data Analysis (EDA) on 3-month daily sales across 5 restaurant branches to identify top performers, evaluate sales consistency, and uncover monthly revenue trends.

---

## Project Overview
This project analyzes 92 days of daily sales performance (**June  – August **) across 5 restaurant branches (`Outlet_A` through `Outlet_E`). By leveraging statistical profiling, distribution checks, and data visualization in Python, this analysis provides actionable insights into branch performance, revenue share, and sales volatility.

---

##  Executive Summary & Performance Ranking

**Total Chain Revenue Generated:** ₹70,95,743.00

| Rank | Outlet | Total Revenue (₹) | Revenue Share (%) | Daily Mean (₹) | Daily Median (₹) | Sales Profile & Volatility |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **#1** | **Outlet_B** | ₹20,53,498 | 28.9% | ₹22,320.63 | ₹21,986.50 | Top Revenue Generator (High Volatility) |
| **#2** | **Outlet_D** | ₹16,59,069 | 23.4% | ₹18,033.36 | ₹18,201.00 | Strong Volume (Highest Fluctuation) |
| **#3** | **Outlet_A** | ₹13,25,154 | 18.7% | ₹14,403.85 | ₹14,646.50 | Steady Performer (Consistent Growth) |
| **#4** | **Outlet_E** | ₹11,32,109 | 16.0% | ₹12,305.53 | ₹12,612.50 | Moderate Volume (Late August Surge) |
| **#5** | **Outlet_C** | ₹9,25,913 | 13.0% | ₹10,064.27 | ₹10,240.50 | Lowest Volume (Most Consistent) |

---

##  Key Findings

* **Market Leader:** **Outlet_B** contributed nearly **29%** of total revenue (₹20.53 Lakhs). Its baseline daily median (₹21,986.50) exceeded every other outlet's peak sales, except Outlet_D.
* **Volatility Analysis:** **Outlet_D** exhibited the highest standard deviation ($\sigma = ₹4,428.41$), signaling significant day-to-day fluctuations.
* **Most Reliable Branch:** **Outlet_C** recorded the lowest standard deviation ($\sigma = ₹2,842.95$) and narrowest range (₹9,789), making it the most predictable outlet for operational planning.
* **Data Quality:** Outlier checks using the Interquartile Range (IQR) method revealed **0 extreme outliers**, confirming steady sales distributions across all branches.

---

##  Tech Stack & Dependencies

* **Language:** Python 
* **Data Processing:** pandas, numpy
* **Data Visualization:** matplotlib, seaborn
* **Environment:** Jupyter Notebook / Google Colab
