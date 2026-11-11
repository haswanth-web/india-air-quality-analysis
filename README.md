# 🇮🇳 India Air Quality Analysis Dashboard (2015–2020)

An end-to-end data analytics project examining historical air pollution trends across 26 major Indian cities using **Power BI, SQL, and Python**.

---

## 📊 Dashboard Preview
![Dashboard Preview](dashboard.png)

---

## 🎯 Project Objective
Analyze over **24,800+ daily air quality records** collected from the Central Pollution Control Board (CPCB) to uncover seasonal pollution patterns, evaluate city-level variations, and assess pollutant concentration levels.

---

## 🔍 Key Business Insights
1. **Seasonal Trends:** Winter (average AQI: **221**) and Post-Monsoon (average AQI: **215**) exhibit the highest pollution spikes, whereas Monsoon records the cleanest air quality (average AQI: **116**).
2. **Geographical Variation:** Inland and northern cities (e.g., Patna, Lucknow) experienced sustained severe AQI levels, while coastal locations (e.g., Kochi, Thiruvananthapuram) maintained significantly lower particulate concentrations.
3. **Category Breakdown:** More than **68%** of the recorded timeline fell under 'Moderate' or 'Satisfactory' air quality brackets, with critical spikes occurring primarily in Q4 of each year.

---

## 🛠️ Tech Stack & Workflow
- **Data Cleaning & Preprocessing:** Python (Pandas, NumPy) for handling missing data, type casting, and standardizing date formats.
- **Data Transformation & Querying:** SQL (aggregations, CTEs, and window functions like `DENSE_RANK` and rolling averages).
- **Business Intelligence & Visualization:** Power BI Desktop (DAX measures, interactive slicers, KPI tracking, and card formatting).

---

## 📁 Repository Structure
- `AQI_Dashboard.pbix` - Complete interactive Power BI report file.
- `dashboard.png` - High-resolution dashboard screenshot.
- `README.md` - Documentation and project summary.
