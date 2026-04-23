# Predicting Hospital Readmissions for Diabetes Patients

## Project Overview
* Objective: Develop an end-to-end healthcare analytics pipeline to predict 30-day hospital readmissions.
* Goal: Reduce healthcare costs and improve patient outcomes through predictive modelling.
* Tools: Python.
* Dataset: Diabetes 130-US Hospitals (1999-2008) - UCI Machine Learning Repository.

---

## Project Workflow
1. Data Acquisition: Sourcing and initial exploration of the clinical dataset.
2. Pre processing & Cleaning: Assessment of data quality, handling missing values, feature engineering, and data transformation.
3. Exploratory Data Analysis (EDA): Univariate and bivariate analysis to identify key insights and patterns.
4. Evaluation: Building predictive models, evaluating performance, and conducting feature importance analysis.

---

## Project Structure
healthcare-readmission-prediction/
├── diabetic_data.csv             # Raw source data
├── diabetic_data_cleaned.csv     # Processed data 
├── healthcare_analytics.py       # Core analysis 
├── EXECUTIVE_SUMMARY.txt         # Project findings and business insights
├── requirements.txt              # Dependencies
├── README.md                     # Project documentation
└── visualizations/               # Exported analysis plots
    ├── 01_target_distribution.png
    ├── 02_numeric_distributions.png
    ├── 03_categorical_distributions.png
    ├── 04_numeric_vs_readmission.png
    ├── 05_categorical_vs_readmission.png
    ├── 06_correlation_matrix.png
    ├── 07_model_comparison.png
    ├── 08_confusion_matrices.png
    ├── 09_feature_importance.png
    ├── 10_probability_distribution.png
    ├── 11_risk_stratification.png
    └── 12_FINAL_DASHBOARD.png

---

## Getting Started

### Prerequisites
Ensure you have Python installed. Install the required libraries using:
pip install -r requirements.txt

### Execution
Run the main analysis script to generate the models and visualizations:
python healthcare_analytics.py

---
Note: This project is part of a comprehensive healthcare analytics initiative. For detailed findings, please refer to the EXECUTIVE_SUMMARY.txt file.