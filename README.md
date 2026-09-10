# Seasonal Agriculture Performance Analysis
*VOIS 4-Week AICTE Internship Major Project (Batch 2026–2027)*

## 📌 Project Overview
This project was developed as part of the 4-week AICTE Internship with Vodafone Idea Foundation (VOIS). It involves comprehensive Exploratory Data Analysis (EDA) on an agricultural dataset consisting of **4,000 records and 28 attributes** to evaluate how crop performance, environmental conditions, resource efficiency, and economic outcomes shift across the Kharif, Rabi, and Zaid seasons.

---

## 📂 Repository Contents
* `Seasonal_Agriculture_Performance_Analysis.ipynb` - Complete executable Jupyter Notebook containing data preprocessing, analysis, and data visualizations.
* `seasonal_agriculture_performance_dataset (1).csv` - The primary agricultural dataset used for analysis.

---

## 🔍 Key Objectives & Implementation
1. **Data Cleaning & Contextual Imputation:** Inspected missing variables and handled missing values using median imputation grouped by State, Season, and Crop.
2. **Seasonal Performance Analysis:** Explored yield variations, total production outputs, and net profitability profiles across different agricultural seasons.
3. **Environmental & Resource Tracking:** Analyzed natural rainfall, ambient temperature, humidity, and resource strains (such as water consumption, fertilizers, and pesticide usage).
4. **Economic & Regional Consistency:** Assessed cost-to-revenue margins and monitored regional profitability resilience across various states.
5. **Statistical Correlations:** Utilized correlation heatmaps to extract hidden dependencies between environmental factors and farm yields.

---

## 📊 Key Findings
* **Kharif Season:** Dominates in terms of productivity and net profitability (~₹1.79L average profit) due to favorable monsoon rainfall (~852 mm).
* **Zaid Season:** Incurs negative net profitability (-~₹24.8K average profit) driven by extreme temperatures (~31°C) and heavy reliance on artificial irrigation overheads (~6,420 m³ water consumption).
* **Regional Resilience:** Northern states like Punjab maintain steady economic margins across dry cycles, whereas southern regions experience sharp performance drop-offs during off-monsoon windows.

---

## 🛠️ Tech Stack
* **Language:** Python 3.10+
* 
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebook
