# HR Analytics & Employee Attrition Prediction

## 📌 Project Overview

Employee attrition is one of the major challenges faced by organizations. High attrition rates can lead to increased recruitment costs, loss of experienced employees, and reduced productivity.

In this project, I analyzed employee data from IBM HR Analytics Dataset to identify the factors influencing employee attrition and built a Machine Learning model to predict whether an employee is likely to leave the company.

The project demonstrates skills in data cleaning, exploratory data analysis (EDA), data visualization, feature engineering, and machine learning model development using Python.

---

## 🎯 Business Problem

Organizations invest significant resources in hiring and training employees. When employees leave unexpectedly, it affects productivity and increases operational costs.

The goal of this project is to:

- Understand employee behavior and attrition patterns.
- Identify key factors that contribute to employee turnover.
- Build a predictive model that can help HR departments identify employees at risk of leaving.

---

## 📂 Dataset Information

Dataset: IBM HR Analytics Employee Attrition Dataset

- Total Rows: 1470
- Total Columns: 35
- Target Variable: Attrition

The dataset contains employee-related information such as:

- Age
- Monthly Income
- Job Role
- Department
- Education
- Years at Company
- Overtime
- Job Satisfaction
- Work-Life Balance
- Attrition Status

---

## 🛠 Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

### Development Environment
- Jupyter Notebook

### Version Control
- Git
- GitHub

---

## 🔍 Project Workflow

### 1. Data Loading
The dataset was imported into Pandas DataFrame and examined to understand its structure and features.

### 2. Data Cleaning
- Checked dataset dimensions
- Inspected data types
- Verified missing values
- Removed unnecessary issues affecting analysis

### 3. Exploratory Data Analysis (EDA)

Several visualizations were created to understand employee behavior:

- Attrition distribution
- Age distribution
- Salary distribution
- Overtime analysis
- Attrition by department
- Attrition by job role

### 4. Data Preprocessing

Categorical variables were converted into numerical values using Label Encoding to make the data suitable for machine learning algorithms.

### 5. Correlation Analysis

A correlation heatmap was generated to understand relationships among different employee attributes.

### 6. Model Building

Logistic Regression was used as the classification algorithm because the target variable (Attrition) contains two classes:

- Yes (Employee Leaves)
- No (Employee Stays)

### 7. Model Evaluation

The model performance was evaluated using:

- Accuracy Score
- Confusion Matrix

---

## 📈 Key Insights

During analysis, several important patterns were observed:

- Employees working overtime showed higher attrition rates.
- Lower monthly income was associated with increased attrition.
- Younger employees were more likely to leave the organization.
- Job satisfaction and work-life balance influenced employee retention.
- Certain job roles experienced higher employee turnover than others.

---

## 🤖 Machine Learning Model

### Logistic Regression

Logistic Regression was selected because:

- It performs well on binary classification problems.
- It is simple and interpretable.
- It provides reliable baseline performance.

Model training included:

- Train-Test Split
- Feature Selection
- Prediction Generation
- Performance Evaluation

---

## 📊 Results

The model successfully classified employee attrition and provided valuable insights into workforce behavior.

The analysis can help HR departments:

- Reduce employee turnover.
- Improve employee satisfaction.
- Identify employees at risk of leaving.
- Make data-driven HR decisions.

---

## 🚀 Future Improvements

Future versions of this project may include:

- Random Forest Classifier
- Decision Tree Classifier
- XGBoost
- Hyperparameter Tuning
- Power BI Dashboard
- SQL Integration
- Employee Attrition Risk Dashboard

---

## 📚 Skills Demonstrated

- Data Cleaning
- Data Analysis
- Data Visualization
- Exploratory Data Analysis
- Machine Learning
- Classification Models
- Feature Engineering
- Git & GitHub
- Problem Solving

---

## 👨‍💻 Author

Nancy Sharma

Aspiring Data Analyst | Python | SQL | Machine Learning | Data Visualization

