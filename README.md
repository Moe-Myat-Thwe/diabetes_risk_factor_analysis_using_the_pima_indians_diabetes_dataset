# 🩺 Diabetes Risk Factor Analysis (EDA)

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on the Pima Indians Diabetes dataset
to identify key medical and demographic factors associated with diabetes.
The goal is to uncover meaningful insights that can support early risk assessment
and data-driven healthcare decisions.

---

## Objectives
- Understand the structure and quality of the dataset
- Identify and handle medically impossible or missing values
- Explore relationships between health indicators and diabetes outcomes
- Summarize actionable insights from exploratory analysis

---

## Dataset Description

Key features include:
- Pregnancies
- Glucose level
- Blood pressure
- Skin thickness
- Insulin
- Body Mass Index (BMI)
- Diabetes Pedigree Function (genetic risk)
- Age
- Outcome (1 = Diabetic, 0 = Non-Diabetic)

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Cleaning & Preparation
- Identified medically impossible zero values in:
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
- Replaced invalid zero values with missing values
- Applied median imputation to handle missing data and reduce the effect of outliers

---

## Exploratory Data Analysis
Key analyses performed:
- Distribution of diabetes outcomes
- Glucose levels vs diabetes outcome
- BMI and age analysis
- Genetic risk (Diabetes Pedigree Function)
- Correlation analysis among features

---

## Key Insights
- Glucose level is the strongest indicator of diabetes risk
- Higher BMI is associated with increased diabetes prevalence
- Diabetes risk increases with age
- Genetic predisposition contributes to diabetes likelihood
- Proper handling of missing medical values significantly improves data reliability

---

## Conclusion
This analysis highlights glucose, BMI, and age as critical factors associated with diabetes.
The insights demonstrate how exploratory data analysis can support early screening
and preventive healthcare strategies.

---

