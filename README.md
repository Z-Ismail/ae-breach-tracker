# 📊 A&E Breach Tracker (Jan–Mar 2025)

This project analyses NHS England A&E performance data using **PySpark** on **Databricks**, focusing on **Type 1 attendances** and **4+ hour breach rates**.

We identify the worst-performing NHS trusts and highlight localised breach trends over a 3-month window.

---

## ⚙️ Tech Stack

- **Platform**: Databricks Community Edition  
- **Language**: PySpark  
- **Libraries**: matplotlib, pandas  
- **Data Source**: [NHS A&E Waiting Times](https://www.england.nhs.uk/statistics/statistical-work-areas/ae-waiting-times-and-activity/)  
- **Visualisation**: Top 20 trusts by average breach rate (horizontal bar chart)

---

## 📁 Data

All datasets are from the official NHS website and cover:

- `ae_jan_2025.csv`  
- `ae_feb_2025.csv`  
- `ae_march_2025.csv`  

Stored in the `/data` folder.

---

## 🔍 Key Insights

- Several trusts breached 50%+ of A&E 4-hour targets.  
- Hull and Mid Cheshire consistently ranked among the worst.  
- Regional filtering (e.g. **"LONDON"**) highlights local performance issues.

---

## 📘 Notebook

Interactive PySpark notebook:  
[`notebooks/ae_breach_tracker.ipynb`](notebooks/ae_breach_tracker.ipynb)

---

## 🚀 Next Steps

- Add Databricks Jobs or scheduling for automation  
- Extend to include ambulance waits, DTA delays, emergency admissions  
- Connect to Power BI / Tableau dashboards

