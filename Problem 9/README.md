
# Student Performance Prediction - ML Pipeline Practice

## Problem Statement

A university wants to predict students' final exam scores based on their academic performance,
attendance, study habits, and department information.

You are provided with a dataset containing both numerical and categorical features.
The dataset also contains missing values, making it ideal for practicing a complete
Machine Learning Pipeline.

Your task is to:

1. Handle missing values
2. Encode categorical data
3. Perform feature scaling
4. Split the dataset into train and test sets
5. Build a regression model
6. Evaluate model performance
7. Create an end-to-end ML pipeline

---

## Dataset Information

### Features

| Column Name | Description |
|---|---|
| study_hours | Average study hours per day |
| attendance_percentage | Student attendance percentage |
| assignment_score | Assignment performance |
| previous_sem_marks | Previous semester marks |
| sleep_hours | Average sleep hours |
| department | Student department (Categorical) |

### Target Column

| Column Name | Description |
|---|---|
| final_exam_score | Final exam score of the student |

---

## Challenges Included in Dataset

- Missing values
- Categorical feature
- Regression problem
- Realistic noisy data

---

## Suggested ML Workflow

### Step 1: Load Dataset
- Use pandas to load CSV

### Step 2: Data Preprocessing
- Handle missing values using:
  - mean/median for numerical columns
  - most frequent for categorical columns

### Step 3: Encoding
- Use OneHotEncoder for department column

### Step 4: Scaling
- Use StandardScaler for numerical features

### Step 5: Build Pipeline
Suggested tools:
- ColumnTransformer
- Pipeline
- SimpleImputer

### Step 6: Train Models
Try:
- Linear Regression
- Random Forest Regressor
- XGBoost
- Decision Tree Regressor

### Step 7: Evaluation Metrics
Use:
- MAE
- MSE
- RMSE
- R² Score

---

## Bonus Tasks

- Perform feature importance analysis
- Save model using pickle/joblib
- Deploy model using Flask/FastAPI
- Add hyperparameter tuning using GridSearchCV

---

## Recommended Folder Structure

project/
│
├── data/
│   └── student_performance_regression_dataset.csv
│
├── notebook/
│   └── eda.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── train.py
│   └── predict.py
│
├── models/
│   └── model.pkl
│
└── README.md

---

Happy Learning 🚀
