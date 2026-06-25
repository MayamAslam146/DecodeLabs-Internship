# Week 1: Advanced EDA & Feature Engineering

## 🎯 Objective
Transform a raw, messy employee dataset into a clean, mathematically sound dataset ready for machine learning.

## 📊 Dataset
`employee_dataset.csv` — 505 rows, 10 columns (age, department, city, years_experience, education, monthly_hours, projects_completed, performance_score, salary).

## ✅ Key Steps
1. **Missing Value Handling** — Median imputation, mode imputation for categoricals, and KNN imputation for columns with >20% missing data (salary).
2. **Outlier Treatment** — Identified and capped outliers using the Interquartile Range (IQR) method.
3. **Feature Engineering** — Created new features: `salary_per_exp_year`, `productivity_ratio`, `experience_level`, `age_exp_interaction`.
4. **Encoding** — One-hot encoded categorical variables (department, city, education, experience_level).
5. **Visualization** — Compared distributions, boxplots, and missing-value patterns before vs. after cleaning.

## 📁 Files
- `Decodelabs_task1.ipynb` — full notebook with code and visualizations
- `employee_dataset.csv` — raw dataset
- `employee_dataset_cleaned.csv` — final cleaned dataset

## 🔑 Key Learning
Data cleaning is not just preprocessing — it's the structural foundation that determines whether a model learns the right patterns or the wrong ones.
