# 📄 COVID-19 Dataset - Exploratory Data Analysis

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a real-world COVID-19 dataset.  
The aim is to understand key health variables, patient demographics, comorbidity impacts, and mortality patterns using statistical and visual techniques.

---

## Dataset Information
- **Records:** 1,048,575 entries
- **Features:** 21 columns
- **Key Columns:**
  - Demographics: `AGE`, `SEX`
  - Health Conditions: `PNEUMONIA`, `DIABETES`, `COPD`, `OBESITY`, etc.
  - Outcomes: `PATIENT_TYPE` (Hospitalized/Outpatient), `DATE_DIED`, `ICU`

---

## Analysis Performed
- **Data Cleaning**: Verified missing values, ensured consistency.
- **Basic Exploration**: Dataset shape, sample rows, and data types.
- **Statistical Summary**: Distribution analysis of age, gender, comorbidities.
- **Data Visualization**:
  - Count plots (Hospitalization status)
  - Pie charts (Gender distribution)
  - Histograms (Age distribution)
  - Correlation heatmaps (Variable relationships)
  - Pairplots (Comorbidities vs. death outcomes)

---

## Key Findings
- **Gender Distribution**: Almost balanced (Females ~50.1%, Males ~49.9%).
- **Age Distribution**: Most patients between 20–60 years; peak between 30–50 years.
- **Mortality Factors**:
  - Older age, pneumonia, and diabetes strongly linked with higher death rates.
  - Presence of multiple health conditions increases mortality risk.
- **Correlations**:
  - Strong positive relation between total cases and deaths.
  - Negative relation between recovery and active case numbers.

---

## Requirements
You need the following Python libraries installed:
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`

(You can install them inside Jupyter Notebook using `!pip install` if needed.)

---

## How to Run
1. Open the provided Jupyter Notebook file.
2. Make sure the dataset (`Covid Data.csv`) is available in the correct path.
3. Run all the cells sequentially to perform the full analysis.

---

## Conclusion
The EDA helped in understanding the major risk factors impacting COVID-19 outcomes.  
Insights gained here can assist in future healthcare planning, early risk detection, and better treatment prioritization during pandemics.
"""


### 👤 Author: Sahil Singh
### 📅 Date: April 28, 2025
### 📝 Task: Task 5 - Exploratory Data Analysis

