# ICU Mortality Rates
### ADS1001 Data Challenges 1 | Semester 1 2022

## Introduction

This project analyses ICU patient data to predict **in-hospital mortality** for ICU Type 1 patients aged 70–90.  
The study compares Day 1 and Day 2 physiological measurements and applies regression-based models to evaluate mortality risk.

## Variables

### Target Variable
- `In_hospital_death` (0 = Survived, 1 = Died)

### Key Features
- Age  
- Mean Weight  
- Mean Respiratory Rate  
- Mean Heart Rate  
- Mean Temperature  
- Mean Cholesterol  
- Mean Glucose  
- Mean Systolic BP  
- Mean Diastolic BP  
- Mean Non-Invasive Systolic BP  
- Mean Urine Output  

(Day 1 `.x` and Day 2 `.y` measurements analysed)

## Project Workflow

1. **Data Filtering**
   - ICU Type 1 only
   - Age 70–90

2. **Preprocessing**
   - Feature selection
   - Separation of Day 1 & Day 2 variables

3. **Modeling**
   - Linear Regression  
   - Logistic Regression  

4. **Evaluation**
   - Train–Test Split (`train_test_split`)
   - R² Score (Linear Regression)
   - Classification Accuracy (Logistic Regression)

<br>

---
## Built With

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/seaborn-4C72B0?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

## License
This project was developed for academic purposes (2022).
If reused or distributed, please provide proper academic attribution.
