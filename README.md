# HR Analytics Using Machine Learning
This repository contains Machine Learning models applied to Human Resource analytics problems. The goal is to use data-driven techniques to support HR decision-making in:
- Salary prediction
- Employee retention (attrition prediction)

### 💼 Salary Prediction Using Machine Learning
This project builds a Machine Learning model using **Linear Regression** to help the HR department predict employee salaries based on:
- Years of experience
- Written test score
- Interview score

The model is trained using historical hiring data and used linear regression to predict salaries for new candidates.

### Employee Retention Prediction (Classification)
The objective of this project id to Predict whether an employee will leave the company using HR metrics such as:
- Satisfaction level
- Last evaluation score
- Number of projects
- Average monthly hours
- Time spent at company
- Promotion history
- Salary level
- Department

Exploratory Data Analysis (EDA)
- Identified strong predictors of attrition
- Found that low satisfaction and low salary significantly increase turnover risk
- Visualized salary and department impact on retention
- Removed duplicate records to ensure model reliability

Model Used
- Logistic Regression

Performance
- Accuracy: 82.9%
- ROC-AUC Score: 0.831

The model demonstrates good discriminatory power in predicting employee attrition.

#### 🛠 Tools & Libraries
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
