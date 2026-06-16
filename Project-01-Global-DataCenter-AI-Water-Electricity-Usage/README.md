# 🌍 Project 01: Global Data Center & AI Water/Electricity Usage Analysis

## 📌 Overview

Data centers and AI workloads are among the fastest-growing consumers of water and electricity worldwide. As demand for cloud computing, artificial intelligence, and large language models continues to increase, understanding their environmental footprint has become a critical challenge.

In this project, I analyze global data center resource consumption across multiple countries, facility types, and years using SQL. The objective is to identify consumption trends, evaluate efficiency, detect anomalies, and generate insights that support sustainability-focused decision-making.

---

## 🎯 Project Objectives

* Analyze water consumption across countries and regions.
* Measure electricity usage trends over time.
* Compare resource efficiency across facility types.
* Identify countries with the highest consumption growth.
* Detect unusual consumption patterns using statistical techniques.
* Forecast future water and electricity demand using CAGR.

---

## 📦 Dataset Information

**Dataset:** Global Data Center & AI Water/Electricity Usage

**Source:** Kaggle

### Dataset Features

| Column                     | Description                               |
| -------------------------- | ----------------------------------------- |
| country                    | Country where the data center is located  |
| year                       | Reporting year                            |
| facility_type              | Type of data center facility              |
| water_usage_million_litres | Annual water consumption (million litres) |
| electricity_usage_gwh      | Annual electricity consumption (GWh)      |
| num_facilities             | Number of facilities tracked              |
| region                     | Geographic region                         |

---

## 🛠️ SQL Skills Demonstrated

### Data Analysis

* GROUP BY
* Aggregate Functions
* Percentage Calculations
* Ranking & Sorting

### Window Functions

* LAG()
* LEAD()
* ROW_NUMBER()
* NTILE()
* Running Totals

### Advanced SQL

* Common Table Expressions (CTEs)
* Subqueries
* Correlated Subqueries
* Cohort Analysis
* Anomaly Detection

### Business Analytics

* Growth Rate Analysis
* Pareto (80/20) Analysis
* Consumption Tier Classification
* Forecasting with CAGR

---

## ❓ Business Questions

### 🔰 Level 1 — Foundational

1. Which countries have the highest total water consumption from data centers?
2. What is the total and average electricity usage globally by year?
3. How many distinct facilities are tracked per country?
4. Which year recorded the highest global water consumption?

---

### ⚙️ Level 2 — Intermediate

5. Calculate year-over-year electricity growth using LAG().
6. Determine each country's contribution to global water consumption.
7. Classify countries into Low, Medium, and High consumption tiers using NTILE().
8. Calculate water-per-electricity efficiency ratios by facility type.

---

### 🔥 Level 3 — Advanced

9. Build a rolling 3-year average of water consumption per country.
10. Identify the top 3 countries by electricity growth rate within each continent.
11. Find countries that consistently appear among the top consumers every year.
12. Build a year-over-year cohort comparison without using self-joins.
13. Detect anomalous consumption patterns using z-score analysis.

---

## 🚀 Challenge Extension

### Forecasting Future Demand

If global AI workloads continue to grow rapidly, what could future water and electricity demand look like?

This extension calculates the Compound Annual Growth Rate (CAGR) for each country and projects estimated resource consumption through 2030.

Formula:

```sql
POWER(latest_value / earliest_value, 1.0 / num_years) - 1
```

---

## 📁 Project Structure

```text
Project-01-Global-DataCenter-AI-Water-Electricity-Usage/
│
├── README.md
├── dataset/
├── sql/
├── screenshots/
└── insights.md
```

---

## 💡 Key Concepts Explored

### Power Usage Effectiveness (PUE)

Measures how efficiently a data center uses energy.

Industry benchmark:

```text
PUE < 1.5
```

### Water Usage Effectiveness (WUE)

Measures litres of water consumed per kWh of IT load.

Industry benchmark:

```text
WUE < 1.0 L/kWh
```

### Data Center Types

* Hyperscale Data Centers (AWS, Azure, Google Cloud)
* Enterprise Data Centers
* AI Training Facilities
* Cloud Infrastructure Facilities

---

## 📈 Expected Outcomes

Through this analysis, we aim to:

* Identify the highest-consuming countries.
* Understand electricity consumption trends.
* Evaluate facility efficiency.
* Detect unusual spikes in resource usage.
* Forecast future sustainability challenges driven by AI growth.

---

## 🏷️ Tools Used

* SQL
* PostgreSQL
* GitHub
* Kaggle Dataset

---
