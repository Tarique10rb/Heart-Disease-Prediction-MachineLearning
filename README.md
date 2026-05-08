# Predictive Machine Learning for Heart Disease

## Overview

This project applies machine learning techniques to predict heart disease using clinical and demographic patient data. The goal was to evaluate how different machine learning algorithms perform in identifying patients at risk for cardiovascular disease.

Using a healthcare dataset containing patient information such as age, cholesterol, blood pressure, and other clinical variables, the project compares Decision Tree and Naïve Bayes classifiers for heart disease prediction.

---

## Background & Significance

Cardiovascular disease remains one of the leading causes of mortality worldwide. Early detection of heart disease risk can improve preventive care and clinical decision-making.

Machine learning models can assist healthcare professionals by identifying hidden patterns within patient data and supporting risk prediction strategies.

---

## Dataset

- Total Records: 1,025 patients  
- Features: 14 clinical and demographic variables  

### Key Variables
- Age
- Sex
- Cholesterol
- Blood Pressure
- Chest Pain Type
- Maximum Heart Rate
- Target Variable:
  - 0 = No Disease
  - 1 = Heart Disease

### Data Source
- Kaggle Heart Disease Dataset

---

## Data Preprocessing

### Preprocessing Steps
- Removed low-variance features with limited predictive value
- Checked target class balance
- Analyzed feature distributions
- Evaluated feature correlations to reduce multicollinearity

### Target Distribution
- No Disease: 54%
- Heart Disease: 46%

---

## Exploratory Data Analysis (EDA)

### Age Distribution
- Majority of patients were between 30–60 years old
- Increased prevalence of heart disease observed in patients aged 50+

### Age vs Cholesterol
- Older patients generally exhibited higher cholesterol levels
- Cholesterol showed moderate association with heart disease risk

### Correlation Analysis
- Heatmaps were used to identify:
  - Feature relationships
  - Redundant variables
  - Predictive clinical features

---

## Machine Learning Models

### Decision Tree Classifier
- Implemented using scikit-learn
- Evaluated using:
  - Accuracy
  - Precision
  - Recall

#### Key Findings
- Achieved higher Recall
- More effective at identifying true positive heart disease cases

---

### Gaussian Naïve Bayes
- Implemented using Gaussian Naïve Bayes classifier
- Evaluated using the same performance metrics

#### Key Findings
- Higher Precision
- Lower Recall due to feature independence assumptions

---

## Model Evaluation

### Metrics Used
- Accuracy
- Precision
- Recall
- Classification comparison

### Results Summary
- Decision Tree performed better for identifying positive heart disease cases
- Naïve Bayes demonstrated simpler but less flexible classification behavior

---

## Key Findings

- Age and cholesterol contributed significantly to prediction performance
- Decision Tree provided stronger sensitivity for disease detection
- Naïve Bayes struggled with correlated clinical variables
- Feature selection improved model robustness

---

## Limitations

- Small dataset size may limit generalization
- Limited hyperparameter tuning
- Potential dataset bias
- Only two machine learning models evaluated

---

## Future Improvements

Potential improvements include:

- Hyperparameter optimization
- Additional machine learning models
- Cross-validation strategies
- Larger and more diverse datasets
- Deep learning approaches for healthcare prediction

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Use Case

This project demonstrates how machine learning can support predictive healthcare analytics and assist in identifying patients at elevated cardiovascular risk.

---

## Key Highlights

- Healthcare predictive analytics
- Exploratory data analysis (EDA)
- Decision Tree classification
- Naïve Bayes classification
- Feature correlation analysis
- Clinical interpretation of ML performance

---

## 👤 Author

Tarique Bagalkot
