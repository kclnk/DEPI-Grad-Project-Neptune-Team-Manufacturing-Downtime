# 🏭 Manufacturing Downtime Analysis  

### DEPI Graduation Project – Neptune Team

  

---

  

## 📌 Overview

Manufacturing downtime directly impacts production efficiency, operational costs, and revenue.

  

This project analyzes **large-scale manufacturing data (1M+ records)** to identify:

- Downtime patterns  

- Root causes of inefficiencies  

- Performance gaps across machines, operators, and shifts  

  

The final output is a **Power BI dashboard** enabling data-driven decision-making for optimizing production and reducing losses.

  

---

  

## 🎯 Objectives

- Analyze **downtime behavior and frequency**

- Measure **production vs target performance**

- Identify **root causes of scrap and inefficiencies**

- Evaluate **machine, workforce, and shift performance**

- Quantify **financial impact (revenue loss)**

  

---

  

## 📊 Dataset

- 📁 Source: DEPI dataset (enhanced with additional tables) :contentReference[oaicite:1]{index=1}  

- 📦 Size: **1M+ rows (scaled analytical model)**  

- 🧩 Structure:

  - Fact Tables: Downtime, Maintenance, Quality  

  - Dimension Tables: Machine, Operator, Product, Shift, Factor  

  

- 🧠 Features:

  - 26+ attributes (time, cost, production, errors, downtime, etc.)

  - Engineered fields:

    - Downtime Events Count  

    - Maintenance Flag  

    - Batch Target Units  

    - Line Efficiency %  
   
    - And more... 

  

---

  

## ⚙️ Data Pipeline

  

### 1. Data Cleaning

- Standardized data types (Date, Time, Numeric)

- Removed duplicates

- Cleaned categorical inconsistencies

- Dropped unnecessary columns  

  

### 2. Feature Engineering

- Created unique IDs (PRD, MCH, OPR, FCT)

- Added analytical metrics for performance tracking  

  

### 3. Data Modeling

- Star Schema:

  - Central Fact: `Downtime Line`

  - Connected to dimensions (Machine, Operator, Product, Shift, Factor)

  

### 4. DAX Layer

Custom measures for:

- Maintenance efficiency  

- Downtime impact  

- Production performance  

- Cost analysis  

  

---

  

## 📈 Dashboard Highlights

  

- Production vs Target trends  

- Downtime distribution across machines  

- Maintenance cost vs duration  

- Shift performance comparison  

- Revenue vs expected revenue  

- Root cause breakdown  

  

---

  

## 🔍 Key Insights

  

### 🚧 Operational Performance Gaps

- Production: **36M vs 39M target → ~3M gap**  

- Scrap: **17M units (very high)**  

- Downtime: **6.58% impacting output**  

  

### 👷 Workforce Insights

- Senior operators contribute **43.6% of errors**  

- ~**2M minutes lost** due to human inefficiencies  

- Performance varies significantly across operators  

  

### 🌙 Shift Performance

- Day shift → highest output **but highest losses (~$1.15M)**  

- Night shift → lowest productivity  

  

### 💰 Financial Impact

- Actual revenue: **654.3M vs 708.9M target → ~55M loss**  

- Orange product line = **highest revenue loss**  

  

### ⚙️ Root Cause Analysis

- Only **21.3%** due to operator errors  

- **78.7% due to technical/external factors** (machines, materials)

  

---

  

## 💡 Recommendations

  

### 🔧 Operations & Maintenance

- Invest in machine reliability  

- Reduce downtime (6.58%) via preventive maintenance  

- Improve quality control to reduce scrap  

  

### 👨‍🏭 Workforce Optimization

- Training for senior operators  

- Targeted coaching for high-error individuals  

- Standardize procedures  

  

### ⏱️ Shift Optimization

- Balance workload across shifts  

- Increase supervision in day shift  

- Improve night shift utilization  

  

### 📊 Business Strategy

- Fix **Orange product losses first (high impact)**  

- Introduce **OEE-based performance metrics**  

- Align production with revenue targets  

  

---

  

## 🛠️ Tools & Technologies

- Power BI  

- DAX  

- Data Modeling (Star Schema)  

- Excel / CSV  

  

---

  

## 📂 Project Structure

```

├── dashboard & reports/ # Power BI (.pbix)

├── data/ # Raw & processed datasets

├── docs/ # Documentation / presentation

├── images/ # Dashboard & Reports screenshots

└── README.md

```

  

---

  

## 🚀 Project Value

This project demonstrates:

- End-to-end data analysis pipeline  

- Business problem solving using data  

- Advanced Power BI & DAX skills  

- Real-world manufacturing insights  

- Ability to handle **large-scale datasets (1M+ rows)**  

  

---

  

## 👨‍💻 Team

Neptune Team – DEPI 2026  

- Diaa Elbanna  

- Fahd Gomaa

- Mohamed Safwat  

- Mohamed Magdy  

- Youssef Mohamed  

  

---

NOTE: Bigger files where just uploaded as samples (Such as data files)

---  

## 📜 License

Educational project under DEPI initiative.
