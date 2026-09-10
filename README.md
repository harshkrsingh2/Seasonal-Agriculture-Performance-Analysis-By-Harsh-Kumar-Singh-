# 🌾 Seasonal Agriculture Performance Analysis

## 📌 Project Overview

This project analyzes seasonal agricultural performance using farm-level data to identify meaningful patterns, relationships, variations, and trends across different agricultural seasons.

The analysis focuses on understanding how agricultural performance changes across **Kharif, Rabi, and Zaid** seasons based on crop yield, environmental conditions, resource utilization, water efficiency, market prices, production costs, revenue, and profitability.

The project was completed as part of the **VOIS AICTE Major Project – Data Analytics**.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand the structure and quality of the agricultural dataset.
- Perform appropriate data cleaning and preparation.
- Identify important seasonal patterns.
- Compare agricultural performance across seasons.
- Analyze relationships among environmental, resource, production, and economic variables.
- Compare performance across crops and regions.
- Investigate resource usage and water efficiency.
- Analyze seasonal economic outcomes.
- Identify significant observations and unusual patterns.
- Develop evidence-based insights and recommendations.

---

## 📊 Dataset

The dataset contains **4,000 farm-level records and 28 variables** covering:

- **Geographical information:** State, District
- **Agricultural information:** Crop, Season, Farm Area
- **Environmental conditions:** Rainfall, Temperature, Humidity, Sunlight, Soil pH, Soil Moisture
- **Nutrients and inputs:** Nitrogen, Phosphorus, Potassium, Fertilizer, Pesticide
- **Farming practices:** Irrigation Method, Seed Quality
- **Production:** Yield, Production
- **Economic variables:** Market Price, Total Cost, Revenue, Profit
- **Water management:** Water Used, Water Efficiency
- **Risk:** Disease/Pest Risk

The dataset covers **3 seasons, 8 crops, and 8 states**.

---

## 🛠️ Technologies Used

### Programming
- Python

### Data Analysis
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Statistical Analysis
- SciPy

### Development Environment
- Google Colab

### Dataset Format
- Microsoft Excel

---

## 🔍 Analysis Performed

### 1. Data Understanding & Cleaning

- Dataset structure and dimensions
- Data types
- Descriptive statistics
- Missing-value analysis
- Missing-value treatment
- Duplicate-record verification
- Feature/variable review

### 2. Exploratory Data Analysis

- Univariate analysis
- Bivariate analysis
- Multivariate analysis
- Seasonal comparisons
- Distribution analysis

### 3. Seasonal Performance Analysis

Compared Kharif, Rabi, and Zaid seasons based on:

- Average yield
- Production
- Revenue
- Cost
- Profit
- Environmental conditions
- Water usage
- Water efficiency

### 4. Environmental Analysis

Analyzed seasonal differences in:

- Rainfall
- Temperature
- Humidity
- Sunlight
- Soil moisture

### 5. Crop & Seasonal Analysis

Investigated:

- Crop performance across seasons
- Crop × Season yield
- Crop × Season profitability
- Best-performing crop-season combinations

### 6. Resource Usage Analysis

Analyzed:

- Irrigation methods
- Fertilizer usage
- Pesticide usage
- Water consumption
- Water efficiency

### 7. Economic Analysis

Compared:

- Market price
- Total cost
- Revenue
- Profit
- Profit margin

across agricultural seasons.

### 8. Regional Analysis

Compared agricultural performance across states and seasons to determine whether seasonal patterns remain consistent across regions.

### 9. Correlation Analysis

Examined relationships between environmental, agricultural, resource, and economic variables using correlation analysis and heatmaps.

### 10. Statistical Validation

A one-way ANOVA was performed to evaluate whether farm-profit differences across Kharif, Rabi, and Zaid seasons were statistically significant.

---

## 📈 Key Findings

Some of the major findings from the analysis include:

- **Kharif recorded the highest average yield at approximately 5.63 tonnes/ha**, followed by Rabi and Zaid.
- **Kharif showed the strongest overall economic performance**, with the highest average profit.
- **Zaid showed weaker economic performance**, with average profit falling below zero.
- Overall seasonal profit margins were approximately **25.17% for Kharif, 14.58% for Rabi, and -4.78% for Zaid**.
- Environmental conditions varied considerably across seasons, particularly rainfall, temperature, humidity, sunlight, and soil moisture.
- **Water efficiency was highest in Kharif and lowest in Zaid** among the three seasons.
- Seasonal agricultural performance was **not consistent across regions**. For example, Punjab showed particularly strong Rabi yield performance, while Karnataka showed strong Zaid performance.
- Crop profitability varied substantially across season-crop combinations, with **Sugarcane and Chilli showing particularly strong profitability** in the analyzed data.
- Statistical testing indicated a **statistically significant difference in farm profit across seasons (p < 0.001)**.



---

## 💡 Recommendations

Based on the analysis:

1. **Adopt region-specific seasonal planning**  
   Agricultural planning should consider regional seasonal performance rather than applying a single strategy across all regions.

2. **Consider crop and season together**  
   Crop selection should be evaluated using both productivity and economic performance.

3. **Improve resource efficiency**  
   Seasonal differences in water usage and water efficiency suggest the need for season-specific resource planning.

4. **Investigate high-performing crop-season combinations**  
   Strong crop-season combinations can be studied further for economically viable agricultural planning.

5. **Monitor environmental conditions**  
   Rainfall, temperature, humidity, sunlight, and soil moisture should be considered when evaluating seasonal agricultural performance.

6. **Investigate low-profit combinations**  
   Loss-making crop-season combinations, particularly those with weaker Zaid performance, require further investigation into cost, environmental, and market factors.

---

## ⚠️ Limitations

- The analysis is based only on the variables available in the provided dataset.
- Correlations indicate associations and should not be interpreted as causal relationships.
- Missing numerical values were handled using median imputation, which may reduce some natural variation.
- The dataset may not capture all real-world agricultural conditions.
- Market prices, environmental conditions, and resource usage may be influenced by factors not included in the dataset.
- Statistical significance does not necessarily imply practical or causal significance.
- The findings should therefore be treated as evidence from the available dataset rather than universal agricultural conclusions.

---

## 📂 Repository Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── Harsh_Kumar_Singh_VOIS_Analysis.ipynb
├── VOIS_Major_project_PPT_By_Harsh_Kumar_Singh.pptx
├── seasonal_agriculture_performance_dataset.xlsx
└── README.md
