# 🧹 HR Data Cleaning Project

This project involves cleaning and preprocessing raw HR data to make it ready for analysis and machine learning tasks. It demonstrates core data preparation techniques such as handling missing values, type conversions, feature transformation, and outlier detection.

## 📌 Problem Statement

The dataset contains employee information like age, salary, job role, and experience. However, it's messy and contains:

- Missing values
- Inconsistent formatting
- Irrelevant or duplicate records
- Numeric and categorical anomalies

The goal is to build a reproducible data cleaning pipeline that prepares this data for accurate and insightful analysis.

## 🛠️ What This Project Covers

- Handling Missing Values (Imputation or Removal)
- Converting Data Types
- Standardizing and Normalizing Numerical Features (like Age, Salary)
- Encoding Categorical Variables

 ## 📁 Files in the Repository

| File | Description |
|------|-------------|
| `hr_data_200_rows.csv` | The raw HR dataset |
| `Data_cleaning_pipeline.ipynb` | Python code for cleaning the HR raw data |
| `hr_data_cleaned.csv` | Cleaned version of the dataset |
| `data_cleaning_pipeline.py` | Python script for cleaning the data |
| `README.md` | This file |

## 🚀 How to Run

1. Clone this repository  

git clone https://github.com/yourusername/hr-data-cleaning.git
cd hr-data-cleaning

2. Install dependencies
   
pip install pandas numpy scikit-learn matplotlib seaborn

3. Run the cleaning script

python data_cleaning_pipeline.py
