# 🌾 US Crop Yield & Climate Sensitivity Dashboard (2017–2022)

## 📌 Project Overview

This project presents a three-page interactive Power BI dashboard analyzing U.S. crop yield trends and climate relationships between 2017 and 2022.

The analysis is aligned with the CropNet framework, which integrates climate-aware agricultural data for county-level yield evaluation. The dashboard explores crop productivity, variability, environmental sensitivity, and regional performance patterns.

---

## 🧠 About CropNet

CropNet is a large-scale multimodal benchmark designed for climate-aware, county-level crop yield prediction. It combines agricultural yield data with weather variables to support research in forecasting and climate impact analysis.

This dashboard utilizes the structured yield and WRF-HRRR weather components to build a business intelligence solution focused on performance analytics.

---

# 📊 Dashboard Pages

---

## 1️⃣ Crop Yield & Climate Overview (2017–2022)

This page provides a high-level executive summary of crop and climate performance.

### Key Components:
- KPI Cards:
  - Average Yield (kg/ha)
  - Total Rainfall (mm)
  - Average Temperature (°C)
  - Average Humidity (%)
- Monthly Temperature Trend (Seasonality)
- Climate Sensitivity Scatter Plots:
  - Temperature vs Yield
  - Humidity vs Yield
  - Rainfall vs Yield
- Interactive Year, Crop, and State filters (Synced across pages)

### Purpose:
To understand overall productivity trends and visually assess climate–yield relationships.

---

## 2️⃣ Crop Yield Dynamics

This page focuses on growth trends, variability, and comparative performance.

### Key Visuals:
- Yield Standard Deviation by Crop (Variability Analysis)
- Yield per Rainfall (Relative Productivity Insight)
- Year-over-Year (YoY) Growth % by Crop
- Yield Trend by Year and Crop
- Average Yield by Crop (Comparison)

### Analytical Focus:
- Identifies most stable vs volatile crops
- Evaluates inter-annual performance fluctuations
- Compares long-term yield consistency

---

## 3️⃣ State-Level Yield Performance & Trends

This page explores geographic productivity differences.

### Key Visuals:
- Top Performing States by Average Yield
- Geographic Yield Map (Bubble Map)
- State × Crop Yield Table
- Crop Coverage Across the US (County Distribution)

### Insights:
- Highlights regional productivity leaders
- Shows crop concentration patterns
- Identifies geographic performance disparities

---

# 🏗 Data Modeling Architecture

A star schema was implemented:

### Fact Tables
- Crop Yield (County-Level, Yearly)
- Weather Data (Monthly Aggregated)

### Dimension Tables
- Calendar (Year & Month Filtering)
- State (FIPS-based relationships)

### Modeling Features
- One-to-many relationships
- Cross-page synchronized slicers
- DAX time-intelligence measures
- Dynamic ranking and variability metrics

---

# 📈 Key DAX Measures

- Average Yield (kg/ha)
- Total Rainfall (mm)
- YoY Growth %
- Yield Standard Deviation
- Yield per Rainfall
- State Ranking

---

# 🔍 Key Insights

- Corn shows the highest productivity but also the highest variability.
- Rainfall demonstrates stronger visible association with yield compared to temperature.
- Cotton production is geographically concentrated in fewer counties.
- Yield patterns remain relatively stable from 2017–2022 with moderate fluctuations.
- Regional differences significantly influence crop performance.

---

# 🛠 Tools & Technologies

- Power BI
- DAX (Time Intelligence, Variability, Ranking)
- Dimensional Data Modeling
- Climate & Agricultural Data Integration

---

# 🚀 Project Highlights

- Built an end-to-end BI solution from climate-aware agricultural data.
- Designed synchronized filtering architecture across multiple pages.
- Implemented star schema modeling for scalable analytics.
- Developed volatility and growth metrics for performance evaluation.
- Created analytical scatter plots to evaluate environmental sensitivity.

---

## 👤 Author

Rushindra Reddy Yasa  
📧 y.rushindrareddy@gmail.com  
🔗 LinkedIn  
💻 GitHub
