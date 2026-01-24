# IABAC Employee Performance Analysis

## Project Overview
This project focuses on analyzing and predicting employee performance for **INX Future Inc.** using data science and machine learning techniques.  
The objective is to identify key factors influencing employee performance and build a predictive model to support HR decision-making.

---

## Business Problem
Employee performance plays a critical role in organizational success.  
The challenge is to analyze historical employee data and:
- Understand performance patterns
- Identify top factors affecting performance
- Predict employee performance ratings accurately

---

## Objectives
- Perform **Exploratory Data Analysis (EDA)**
- Identify **top 3 factors** affecting employee performance
- Build and evaluate **machine learning models**
- Recommend strategies to improve employee performance

---

## Dataset Information
- Organization: INX Future Inc.
- Records: 1200 employees
- Features: 28 (Numerical, Categorical, Ordinal)
- Target Variable: **PerformanceRating**

> Note: The dataset is provided by IABAC™ for academic purposes.

---

## Project Structure

```
iabac-employee-performance-analysis/
├── DATA/
│   └── employee_dataset.csv
├── SRC/
│   ├── data_processing/
│   │   ├── data_processing.ipynb
│   │   └── eda.ipynb
│   ├── models/
│   │   ├── training.ipynb
│   │   └── model.pkl
│   └── visualization/
│       └── visualization.ipynb
├── SUMMARY/
│   └── summary_of_the_project.md
├── README.md
├── LICENSE
└── .gitignore
```


---
## Data Preprocessing
- Missing value check
- Encoding categorical features
- Outlier handling using IQR
- Feature scaling using StandardScaler
- Feature selection using correlation & PCA

---

## Machine Learning Models Used
- Support Vector Machine (SVM)
- Random Forest Classifier
- Artificial Neural Network (MLP)

### Final Model Selected
- **Artificial Neural Network (MLP)**
- Test Accuracy: **95.80%**

---

## Key Insights
- Employee Environment Satisfaction is the most influential factor
- Salary hike percentage strongly impacts performance
- Work-life balance improves employee efficiency

---

## Tools & Libraries
**Tools**
- Jupyter Notebook

**Libraries**
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Pickle

---

## Conclusion
The project successfully identifies critical factors affecting employee performance and delivers a robust predictive model.  
The insights and recommendations can help organizations improve productivity and employee satisfaction.

---

## Author
**Saniya Jasmin Shaik**  
Certified Data Scientist – IABAC™  

