# India Water Quality Analysis Dashboard

A comprehensive **Power BI Dashboard** project that analyzes water quality across different Indian states using chemical, biological, and physical water quality parameters. The project provides interactive visualizations and data-driven insights to identify contamination patterns, evaluate Water Quality Index (WQI), and support better environmental decision-making.



## 📌 Project Overview

Water quality plays a vital role in public health and environmental sustainability. This project analyzes **1,000 water samples** collected from **17 Indian states** and **7 different water sources**. Using **Power BI** and **Power Query**, the dataset was cleaned, transformed, and visualized to generate meaningful insights about water quality across India.

The dashboard helps identify:
- Heavy metal contamination
- Water Quality Index (WQI) performance
- Regional water quality differences
- Chemical and mineral properties
- Biological contamination



## 🎯 Objectives

- Analyze water quality across different Indian states.
- Identify areas with high chemical contamination.
- Compare Water Quality Index (WQI) among states.
- Study biological pollution indicators.
- Build an interactive Power BI dashboard for data visualization.
- Generate actionable recommendations for water quality improvement.



## 📂 Dataset Information

- **Total Samples:** 1,000
- **States Covered:** 17
- **Water Sources:** 7

### Dataset Features

- Sample ID
- State
- Water Source
- pH
- Temperature
- Turbidity
- Dissolved Oxygen (DO)
- Biological Oxygen Demand (BOD)
- Chemical Oxygen Demand (COD)
- Lead
- Nitrate
- Fluoride
- Calcium
- Magnesium
- Hardness
- Total Coliform
- Water Quality Index (WQI)
- WQI Classification


# 🛠️ Data Cleaning & Preprocessing

Data preprocessing was performed using **Power Query Editor** before visualization.

### Steps Performed

- Standardized column names and text values
- Corrected inconsistent state names
- Removed extra spaces and formatting issues
- Handled missing values
- Removed invalid records
- Identified and treated outliers
- Verified data types
- Prepared analysis-ready dataset
- Used cleaned dataset for dashboard creation



# 📊 Dashboard Sections

## 1️⃣ Heavy Metals & Chemical Contamination

Analyzes:

- Lead Concentration
- Nitrate Levels
- Fluoride Levels
- Biological Risk

Key Findings

- Haryana and Maharashtra showed higher Lead concentration.
- High Nitrate values were observed in isolated samples.
- Groundwater and Well water contained higher Fluoride concentrations.
- Nearly 42.8% of samples belonged to the Poor biological-risk category.

---

## 2️⃣ Water Quality Index (WQI) Performance

Analyzes

- Average WQI
- WQI Classification
- State-wise Performance

Key Findings

- Average WQI = **86.76**
- 33.7% samples are Excellent
- 65.3% samples are Good
- Haryana and Bihar showed better WQI performance.

---

## 3️⃣ Regional Water Quality Analysis

Analyzes

- State-wise comparison
- Regional ranking

Key Findings

- Odisha achieved the highest average WQI.
- Bihar and Haryana followed closely.
- Punjab and West Bengal recorded comparatively lower scores.

---

## 4️⃣ Chemical Properties

Analyzes

- Hardness Distribution
- Calcium vs Magnesium
- Chloride vs Sulfate
- Average pH by Water Source

Key Findings

- Most samples contained moderately hard water.
- Groundwater maintained a stable pH.
- High Chloride outliers indicate possible saline intrusion.

---

## 5️⃣ Biological Health Analysis

Analyzes

- Total Coliform
- BOD vs COD
- Dissolved Oxygen
- Biological impact on WQI

Key Findings

- River and Lake sources showed higher bacterial contamination.
- Higher BOD and COD resulted in lower WQI.
- Dissolved Oxygen showed a slight declining trend.


# 📈 Technologies Used

- Microsoft Power BI
- Power Query Editor
- Microsoft Excel / CSV Dataset


# 📊 Dashboard Features

- Interactive Visualizations
- KPI Cards
- Bar Charts
- Pie Charts
- Scatter Plots
- Line Charts
- State-wise Comparison
- Dynamic Filtering
- Data-driven Insights



# 📁 Project Structure

```
India-Water-Quality-Analysis/
│
├── Dashboard.pbix
├── water_quality_index_dataset.csv
├── India_Water_Quality_Analysis.pptx
├── README.md

```




# 💡 Key Insights

- Chemical contamination is concentrated in specific states.
- Overall water quality is good, but excellent-grade water remains limited.
- Regional differences significantly affect water quality.
- Most mineral properties remain stable.
- Biological contamination strongly impacts Water Quality Index.


# 🚀 Future Scope

- Integrate real-time IoT sensor data.
- Add predictive analytics using Machine Learning.
- Include GIS-based location mapping.
- Develop automated alert systems.
- Expand the dashboard with yearly trend analysis.



