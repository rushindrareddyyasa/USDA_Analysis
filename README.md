# 🌾 US Crop Yield & Climate Sensitivity Dashboard (2017–2022)

## 📌 Project Overview

This project presents a three-page interactive Power BI dashboard analyzing U.S. crop yield trends and climate relationships between 2017 and 2022.

The analysis is aligned with the **CropNet benchmark framework**, a large-scale multimodal dataset and deep learning package designed for climate-aware, county-level crop yield prediction.

🔗 Official CropNet Benchmark (Hugging Face):  
https://huggingface.co/datasets/CropNet/CropNet

This repository contains data preprocessing notebooks, cleaned datasets, and the final Power BI dashboard file.

---


---

# 📊 Data Sources

### 🔹 CropNet Benchmark
Multimodal climate-aware agricultural dataset integrating satellite imagery and weather data.

### 🔹 USDA Crop Yield Data
County-level yield data for:
- Corn
- Wheat
- Soybeans
- Cotton

### 🔹 WRF-HRRR Weather Data
Monthly aggregated metrics:
- Average Temperature (°C)
- Total Rainfall (mm)
- Average Humidity (%)

---

# 🛠 Data Processing Workflow

The following notebooks were used for preprocessing:

### 📓 `crop_yield_DA.ipynb`
- Cleaned raw USDA yield data
- Standardized units (converted to kg/ha)
- Created FIPS mapping
- Prepared county-level yearly dataset

### 📓 `Weather_data.ipynb`
- Aggregated grid-level weather data
- Converted temperature from Kelvin to Celsius
- Aggregated daily → monthly → yearly metrics
- Generated county-level weather dataset

---

# 📁 Processed Files

### ✅ `USDA_Crop_Yield.csv`
Cleaned and standardized county-level yearly crop yield dataset.

### ✅ `Weather_data_monthly.csv`
Monthly aggregated county-level weather metrics.

### ✅ `cropnet.pbix`
Final Power BI dashboard with:
- Star schema modeling
- Synced slicers
- Climate–yield scatter analysis
- Yield variability metrics
- State-level performance analysis

---

# 📈 Dashboard Pages

## 1️⃣ Crop Yield & Climate Overview
- KPI cards (Yield, Rainfall, Temperature, Humidity)
- Monthly temperature seasonality
- Climate sensitivity scatter plots

## 2️⃣ Crop Yield Dynamics
- Yield Standard Deviation
- Yield per Rainfall
- Year-over-Year Growth
- Trend analysis by crop

## 3️⃣ State-Level Yield Performance & Trends
- Top performing states
- Yield map visualization
- State × Crop comparison table
- Crop coverage across counties

---

# 🚀 Key Highlights

- Applied CropNet-aligned climate-aware agricultural data
- Built star schema model for scalable filtering
- Implemented DAX time intelligence measures
- Designed interactive multi-page BI dashboard
- Transformed raw climate and yield data into analytical insights

---


---

## 👤 Author

**Rushindra Reddy Yasa**

📧 Email: [y.rushindrareddy@gmail.com](mailto:y.rushindrareddy@gmail.com)  
🔗 LinkedIn: [Rushindra Reddy Yasa](https://www.linkedin.com/in/rushindrareddy-yasa-1b554231a)  
💻 GitHub: [rushindrareddyyasa](https://github.com/rushindrareddyyasa)

---
