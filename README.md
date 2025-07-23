# Predictive Modeling of Cardiovascular Conditions

## Project Overview

This project analyzes a dataset of 1000 patient records to identify key predictors of cardiovascular disease. Using logistic regression and exploratory data analysis, we investigate how various clinical features such as age, gender, blood pressure, and heart rate relate to the presence or absence of heart disease.

The analysis is written in **R Markdown** and rendered as an **HTML report** for reproducibility and readability.

---

## Files

- `cardio_disease.Rmd` — R Markdown file containing the full analysis
- `cardio_disease.html` — Rendered HTML report
- `cardio_data.xlsx` — Dataset containing patient records *(sourced from Kaggle)*

---

## Features Used

- **Age** (years)
- **Gender** (binary: 1 = male, 0 = female)
- **Resting Blood Pressure** (mm Hg)
- **Maximum Heart Rate Achieved**
- **Disease** (binary target: 1 = disease present, 0 = absent)

---

## Methods

- **Data Cleaning & Preprocessing**
- **Descriptive Statistics**
- **Correlation Analysis**
- **Logistic Regression Modeling**
- **Model Interpretation and Diagnostics**

---

## Results Summary

- Logistic regression identified **age** and **maximum heart rate** as significant predictors.
- The final model provides insight into the **likelihood of heart disease** based on easily collected clinical features.
