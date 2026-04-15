# Life Expectancy Prediction & Policy Simulation using Machine Learning

## Project Overview

This project analyzes global health, economic, and social factors to predict life expectancy using machine learning models. It also simulates policy interventions to estimate their impact on population longevity.

---

## Problem Statement

Life expectancy is a critical indicator of a country’s health and development. However, identifying the most influential factors and understanding how policy changes affect longevity remains challenging.

This project aims to:

* Predict life expectancy using historical data
* Identify key drivers of longevity
* Simulate policy improvements to support decision-making

---

## Dataset

* Source: World Health Organization (WHO)
* Includes health, economic, and demographic indicators across countries

### Key Features:

* Adult Mortality
* Infant & Under-5 Deaths
* GDP (log-transformed)
* Schooling
* Immunization Coverage
* Health Expenditure

---

## Approach

### 1. Data Preprocessing

* Handled missing values using median/mode imputation
* Removed duplicates
* Encoded categorical variables
* Log transformation applied to GDP

### 2. Feature Engineering

* Created **Health Index** combining:

  * BMI
  * Immunization indicators

### 3. Model Building

Implemented:

* Linear Regression
* Random Forest

### 4. Evaluation Metrics

* R² Score
* RMSE (Root Mean Squared Error)

---

## Results

* Random Forest achieved high accuracy:

  * **R² Score ≈ 0.96**
  * **Low RMSE (~1.68)**

* Outperformed linear models by capturing non-linear relationships

---

## Key Insights

* Education is a major driver of life expectancy
* Adult mortality has the strongest negative impact
* Preventive healthcare significantly improves lifespan
* GDP alone is not sufficient — social factors matter more
* Machine learning enables data-driven policy decisions

---

## Policy Simulation (What-if Analysis)

This project simulates real-world interventions:

### Example:

* Increasing schooling by 1 year
* Increasing healthcare expenditure

 Result:

* Measurable improvement in predicted life expectancy

---

## Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## Key Feature

This project goes beyond prediction by acting as a **decision-support tool**, helping policymakers evaluate the impact of potential interventions.

---

## Future Improvements

* Use advanced models (XGBoost)
* Deploy using Streamlit
* Add interactive dashboard
* Use real-time data

---

## Conclusion

The model not only predicts life expectancy accurately but also provides actionable insights for improving public health through data-driven policy decisions.

---

## Author

Shruti Mandale
