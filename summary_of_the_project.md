# Employee Performance Analysis

## Project Overview
The objective of this project is to analyze employee performance data and identify the key factors that influence employee performance ratings. The project also aims to build a machine learning model to predict employee performance and provide actionable recommendations to improve organizational productivity.

---

## Goal 1: Data Understanding and Preparation
The employee performance dataset was analyzed and preprocessed by handling missing values, removing duplicate records, encoding categorical variables, and applying feature engineering techniques. The cleaned dataset was prepared for exploratory data analysis and model building.

---

## Goal 2: Top Factors Affecting Employee Performance
Based on exploratory data analysis and feature importance techniques, the top three factors affecting employee performance are:

1. Employee Environment Satisfaction  
   Employees with higher environment satisfaction levels (Level 3 and Level 4) show better performance ratings.

2. Salary Hike Percentage  
   Employees receiving salary hikes between 11%–19% mostly fall under performance ratings 2 and 3, while those receiving hikes between 20%–22% often achieve the highest performance rating.

3. Years of Experience in Current Role  
   Employees with more experience in their current role tend to perform better due to increased skill and role familiarity.

---

## Goal 3: Model Building and Evaluation
Multiple machine learning models were trained and evaluated to predict employee performance:

- Support Vector Classifier (SVC) achieved high accuracy but showed signs of overfitting.
- Artificial Neural Network (Multilayer Perceptron) provided balanced performance with good generalization.
- Random Forest Classifier performed well on training data but showed slightly lower test accuracy after tuning.

Based on overall performance and generalization capability, the Artificial Neural Network (Multilayer Perceptron) model was selected as the final model.

---

## Goal 4: Recommendations to Improve Employee Performance
Based on the analysis, the following recommendations are suggested:

- Improve employee work environment and satisfaction levels.
- Provide timely and performance-based salary hikes.
- Promote employees at regular intervals based on performance.
- Encourage a healthy work-life balance.
- Focus on high-performing departments such as Development and Sales.
- Support employees with lower job and relationship satisfaction, as they still demonstrate strong performance potential.

---

## Conclusion
This project successfully identifies the key factors affecting employee performance and builds a predictive model to support data-driven decision-making. The insights and recommendations derived from this analysis can help organizations improve employee performance and overall productivity.
