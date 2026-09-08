# Agriculture_Analysis_Project
## 📌 Project Overview
This project performs a comprehensive analysis of agricultural farm data to understand the relationship between **season, crop type, irrigation methods, environmental factors, yield, water efficiency, and profitability**.

The analysis uses a dataset containing agricultural farm records from different states, districts, crops, and seasons. The project applies **data cleaning, exploratory data analysis (EDA), statistical analysis, visualization, and performance evaluation** to identify important agricultural trends.

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze agricultural farm data from different regions.
* Identify the best season based on crop yield.
* Identify the most profitable agricultural season.
* Determine which crop provides the highest yield.
* Identify the most profitable crop.
* Compare different irrigation methods.
* Analyze water efficiency across irrigation methods.
* Study the relationship between environmental factors and crop yield.
* Perform correlation analysis.
* Apply ANOVA statistical testing to analyze seasonal differences.
* Generate cleaned datasets and Excel reports.

## 📂 Dataset

The dataset contains agricultural farm-level records with approximately **4000 records**.

### Important Features

| Feature                       | Description                                |
| ----------------------------- | ------------------------------------------ |
| Farm_ID                       | Unique identification number for each farm |
| State                         | State where the farm is located            |
| District                      | District where the farm is located         |
| Crop                          | Type of crop cultivated                    |
| Season                        | Agricultural season                        |
| Farm_Area_Hectares            | Total farm area                            |
| Rainfall_mm                   | Rainfall received                          |
| Avg_Temperature_C             | Average temperature                        |
| Humidity_pct                  | Humidity percentage                        |
| Sunlight_Hours_Day            | Daily sunlight hours                       |
| Soil_pH                       | Soil pH level                              |
| Soil_Moisture_pct             | Soil moisture percentage                   |
| Nitrogen_kg_ha                | Nitrogen content                           |
| Phosphorus_kg_ha              | Phosphorus content                         |
| Potassium_kg_ha               | Potassium content                          |
| Irrigation_Method             | Type of irrigation used                    |
| Fertilizer_kg_ha              | Fertilizer usage                           |
| Pesticide_Litre_ha            | Pesticide usage                            |
| Seed_Quality_Score            | Seed quality score                         |
| Yield_Tonnes_Ha               | Crop yield                                 |
| Production_Tonnes             | Total crop production                      |
| Market_Price_INR_Tonne        | Market price                               |
| Total_Cost_INR                | Total farming cost                         |
| Revenue_INR                   | Total revenue                              |
| Profit_INR                    | Total profit                               |
| Water_Used_m3                 | Total water used                           |
| Water_Efficiency_t_per_1000m3 | Water efficiency                           |
| Disease_Pest_Risk_pct         | Disease and pest risk                      |

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* OpenPyXL
* Google Colab / Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Collection

The agricultural dataset is loaded into Python using Pandas.

### 2. Data Cleaning

The following preprocessing steps are performed:

* Checking dataset structure.
* Checking missing values.
* Handling missing numerical values using the median.
* Handling missing categorical values using the mode.
* Detecting duplicate records.
* Removing duplicate records.

### 3. Exploratory Data Analysis

The project analyzes:

* Crop distribution.
* Season distribution.
* Statistical summary of numerical features.
* Yield patterns.
* Profit patterns.

### 4. Seasonal Analysis

The following comparisons are performed:

* Average yield by season.
* Average profit by season.

### 5. Crop Analysis

The following comparisons are performed:

* Average yield by crop.
* Average profit by crop.

### 6. Irrigation Analysis

Different irrigation methods are compared based on:

* Average crop yield.
* Water efficiency.

### 7. Environmental Analysis

The relationship between yield and environmental variables is analyzed.

Variables include:

* Rainfall.
* Temperature.
* Soil moisture.

### 8. Correlation Analysis

A correlation matrix and heatmap are generated to study relationships between numerical variables.

### 9. Statistical Analysis

ANOVA tests are performed to determine whether seasonal differences are statistically significant for:

* Crop yield.
* Farm profit.

### 10. Results Export

The project generates:

* Cleaned CSV dataset.
* Excel analysis report.

---

# 📈 Visualizations

The project generates the following visualizations:

* 📊 Average Yield by Season
* 📊 Average Profit by Season
* 🌾 Average Yield by Crop
* 💰 Average Profit by Crop
* 💧 Yield by Irrigation Method
* 💧 Water Efficiency by Irrigation Method
* 🌧️ Rainfall vs Yield
* 🌡️ Temperature vs Yield
* 🌱 Soil Moisture vs Yield
* 🔥 Correlation Heatmap

---

# 🔍 Key Findings

Based on the analysis:

### 🌾 Performance Summary

* Best Season by Yield: **Kharif**
* Best Season by Profit: **Kharif**
* Best Crop by Yield: **Sugarcane**
* Most Profitable Crop: **Sugarcane**

### 💧 Resource Summary

* Best Irrigation Method by Yield: **Drip**
* Best Irrigation Method by Water Efficiency: **Rainfed**

### 📈 Statistical Results

| Analysis     |      P-Value |
| ------------ | -----------: |
| Yield ANOVA  |     0.213678 |
| Profit ANOVA | 1.71 × 10⁻¹⁵ |

### Interpretation

* The ANOVA p-value for **yield** is greater than 0.05, indicating that the observed differences in average yield between seasons are not statistically significant.
* The ANOVA p-value for **profit** is less than 0.05, indicating a statistically significant difference in profit between seasons.

---


# 📦 Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scipy
openpyxl
```

---

# 💾 Output Files

After running the project, the following files are generated:

### 1. Cleaned Dataset

```text
cleaned_seasonal_agriculture_data.csv
```

This file contains the cleaned agricultural dataset after handling missing values and duplicate records.

### 2. Excel Analysis Report

```text
Agriculture_Analysis_Results.xlsx
```

The Excel file contains multiple sheets including:

* Cleaned Data
* Season Yield Analysis
* Season Profit Analysis
* Crop Yield Analysis
* Crop Profit Analysis
* Irrigation Yield Analysis
* Water Efficiency Analysis

---

# 🧪 Statistical Testing

The project uses **One-Way ANOVA (Analysis of Variance)**.

### Null Hypothesis

There is no significant difference between the seasonal groups.

### Alternative Hypothesis

There is a significant difference between at least one seasonal group.

### Decision Rule

```text
If P-Value < 0.05
→ Reject Null Hypothesis

If P-Value ≥ 0.05
→ Fail to Reject Null Hypothesis
```

---

# 🔮 Future Improvements

The project can be extended with:

* 🤖 Machine Learning Yield Prediction
* 💰 Profit Prediction
* 🌦️ Weather-Based Crop Recommendation
* 🌱 Soil-Based Crop Recommendation
* 🚜 Fertilizer Recommendation System
* 💧 Smart Irrigation Recommendation
* 📊 Interactive Dashboard using Streamlit
* 🔥 Advanced Machine Learning Models
* 🧠 Deep Learning Models
* 📱 Web Application for Farmers

---

# 👨‍💻 Author

**Siddhesh Gupta**


# ⭐ Conclusion

This project provides a comprehensive analysis of agricultural farm data using Python. It identifies important patterns related to **crop yield, profitability, irrigation methods, water efficiency, environmental factors, and agricultural seasons**.

The project demonstrates practical skills in:

* Data Cleaning
* Data Analysis
* Data Visualization
* Statistical Testing
* Python Programming
* Agricultural Data Analytics

