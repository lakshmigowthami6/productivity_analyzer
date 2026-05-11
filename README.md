# Digital Procrastination Financial Loss Predictor using Linear Regression

## Overview

This project analyzes how digital behavior patterns such as screen time, app usage, productivity habits, and attention span impact overall productivity and potential financial loss caused by procrastination.

Using **Exploratory Data Analysis (EDA)**, **Feature Engineering**, and **Linear Regression models (including Ridge and Lasso)**, this project predicts productivity-related outcomes and quantifies the cost of digital distraction.

---

## Problem Statement

Excessive screen time and poor digital habits can reduce productivity, attention span, and effective work output.

This project aims to:

* Analyze productivity patterns based on digital behavior
* Predict productivity scores using regression techniques
* Identify major contributing factors to procrastination
* Estimate the indirect financial or productivity loss associated with poor digital habits

---

## Dataset

### Source:

Kaggle Productivity and Screen Time Dataset

### Features Include:

* Age Group
* Gender
* Education Level
* Occupation
* Average Screen Time
* Device Type
* Screen Activity
* App Category
* Environment
* Productivity Level
* Attention Span
* Notification Handling
* Productivity App Usage

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Workflow

### 1. Data Cleaning

* Removed duplicates
* Handled categorical variables
* Encoded ordinal and nominal features
* Standardized numerical inputs

---

### 2. Exploratory Data Analysis

Performed:

* Histograms
* Boxplots
* Correlation Heatmaps
* Distribution Analysis
* Outlier Detection

---

### 3. Feature Engineering

Created:

* Productivity score mappings
* Screen time ordinal encodings
* Behavioral indicators
* Procrastination-related variables

---

### 4. Model Building

Implemented:

* Linear Regression
* Ridge Regression
* Lasso Regression

---

### 5. Evaluation Metrics

Used:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

---

## Results

### Linear Regression Performance:

* R² Score: ~0.82
* MAE: ~805
* MSE: ~1,499,636
* RMSE: ~1225

### Key Insights:

* Digital habits strongly impact productivity
* Screen time alone is insufficient; behavior context matters
* Feature engineering significantly improved model performance
* Regularization can further optimize generalization

---

## Key Learnings

* Importance of preprocessing and EDA
* Ordinal vs nominal encoding strategies
* Regression assumptions
* Ridge and Lasso regularization
* Real-world behavioral data complexity

---

## Future Improvements

* Deploy as Streamlit web app
* Add real-time user behavior input
* Improve financial loss estimation
* Expand with larger datasets
* Integrate advanced ensemble models

---

## Project Structure

```txt
├── Productivity_Linear_Regression.ipynb
├── README.md
├── requirements.txt
└── dataset/
```

---

## Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Run the Project

```bash
jupyter notebook Productivity_Linear_Regression.ipynb
```

---

## Resume Value

This project demonstrates:

* End-to-end ML workflow
* Real-world data preprocessing
* Regression modeling expertise
* Feature engineering
* Performance optimization
* Practical behavioral analytics

---

## Conclusion

This project showcases how machine learning can be applied beyond traditional prediction tasks to evaluate real-world behavioral productivity and procrastination patterns.

By combining data science with behavioral analysis, this model provides meaningful insights into the measurable cost of digital distraction.

---

## Author

Gowthami

---
