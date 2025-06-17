# ACIS Car Insurance Analytics – Task 1

## 📊 Overview

This repository contains the analysis for **Task 1** of the ACIS (AlphaCare Insurance Solutions) car insurance analytics project. The aim of this task is to explore the historical insurance dataset to gain insights into claim behavior, customer profiles, and regional risk distribution. The findings will guide marketing and pricing strategy optimization.

---

## 🧠 Business Context

AlphaCare Insurance Solutions is focused on identifying low-risk clients and enhancing its marketing efforts through data-driven insights. Task 1 focuses on:
- Understanding the structure and quality of the data
- Performing initial Exploratory Data Analysis (EDA)
- Applying statistical reasoning to uncover trends in risk and profitability

---

## 📌 Objectives for Task 1

- Set up Git version control and CI/CD via GitHub Actions
- Understand the data structure and clean the dataset
- Compute and analyze key insurance KPIs such as **Loss Ratio**
- Detect outliers and visualize claim patterns across time, geography, gender, and vehicle features
- Identify potentially profitable or high-risk client segments

---

## 🛠️ Technologies Used

- **Python 3.10**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Statsmodels**, **Scipy** – Statistical analysis
- **Git & GitHub** – Version control and collaboration
- **GitHub Actions** – CI/CD for code linting and checks

---


---

## 📈 Key Insights Explored

- **Loss Ratio Trends**: TotalClaims / TotalPremium computed across `Province`, `Gender`, and `VehicleType`
- **Temporal Patterns**: Monthly claim frequency and severity over the 18-month period
- **High-Risk Vehicles**: Make/Model combinations associated with the highest average claims
- **Outlier Detection**: Boxplots to highlight anomalies in claims and vehicle value
- **Data Quality Checks**: Missing values, unexpected dtypes, and consistency issues

---

## 📅 Timeline & Commit Strategy

- A dedicated branch `task-1` is used for all developments.
- Commits follow a clear structure (e.g., `Load dataset and initial profiling`, `Added loss ratio visualizations`, `CI setup via GitHub Actions`).
- Commits are made at least 3 times per day.

---

## ✅ Task 1 Deliverables

- [x] GitHub repo with `task-1` branch and CI/CD
- [x] EDA and statistical analysis notebook
- [x] Loss ratio exploration by geography, vehicle, and gender
- [x] 3+ well-designed visualizations
- [x] Outlier analysis using boxplots
- [x] Correlation matrix and time series plots

---






