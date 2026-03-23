# Quality-Allocation-Performance-Dashboard-Power-BI-
Power BI dashboard analyzing QA performance, allocation efficiency, and delivery trends. Tracks pre-QA, post-QA, DQ%, and qualification rates using interactive visuals, DAX, and star schema modeling to identify performance gaps and optimize operations.

# 📊 Quality & Allocation Performance Dashboard (Power BI)

## 🔹 Project Overview

This project analyzes quality audit and allocation data to monitor performance, track delivery efficiency, and identify operational gaps using an interactive Power BI dashboard.

## 🔹 Business Problem

Organizations need visibility into QA performance, allocation efficiency, and delivery trends to improve quality outcomes and optimize resource utilization.

## 🔹 Data Sources

* QA Audit Data (Pre-QA, Post-QA)
* Allocation Data
* Campaign & Client Data
* Auditor Details

## 🔹 Key Metrics Tracked

* Target %
* Pre-QA Volume
* Post-QA Volume
* Total DQ
* Qualification %
* DQ %

## 🔹 Key Analysis

* Weekly trend of Qualified vs Pre-QA vs Leads Required
* Client-wise performance comparison
* Allocation vs output tracking
* Auditor-level filtering and analysis
* Post-QA vs Target achievement

## 🔹 Data Modeling

Implemented **Star Schema**:

* Fact Table: QA / Transaction Data
* Dimension Tables: Client, Campaign, Auditor, Date

## 🔹 Dashboard Features

* KPI Cards (Target %, Pre-QA, Post-QA, DQ%, Qualification %)
* Weekly trend line analysis
* Client-wise performance bar chart
* Funnel view (Pre-QA → Allocation → DQ → Qualified)
* Gauge visual for target tracking
* Interactive slicers (Channel, Campaign Level, Auditor, Date)

## 🔹 Key Insights

* Clear gap between Pre-QA and Qualified output
* Certain clients contribute higher volume but lower efficiency
* Weekly trends highlight fluctuation in performance
* Allocation directly impacts final qualification output
* DQ% helps identify quality drop areas

## 🔹 Tools Used

* Power BI
* DAX
* Data Modeling (Star Schema)
* Data Visualization

## 🔹 Project Outcome

This dashboard enables stakeholders to monitor quality performance, track allocation efficiency, and take data-driven decisions to improve operational outcomes.
