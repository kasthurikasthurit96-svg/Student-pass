# Student Exam Pass Prediction System using Logistic Regression

## Project Overview

The **Student Exam Pass Prediction System** is a Machine Learning project developed to predict whether a student is likely to **Pass** or **Fail** 
in the final examination. The system uses **Logistic Regression** along with **Exploratory Data Analysis (EDA)** and interactive visualizations to 
analyze student academic performance.

Educational institutions collect large amounts of student-related data such as attendance, study hours, previous exam scores, 
and extracurricular participation. This project helps identify students who may be academically at risk and supports early intervention strategies.

---

# Objectives

* Analyze student academic performance data
* Perform Exploratory Data Analysis (EDA)
* Identify factors affecting student success
* Predict Pass/Fail outcomes using Logistic Regression
* Detect high-risk students
* Build an interactive dashboard using Streamlit

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Plotly
* Streamlit

---

# Dataset Information

## Dataset Source

Kaggle

## Dataset Name

Student Performance Prediction Dataset

## Features Used

| Column Name                | Description               |
| -------------------------- | ------------------------- |
| Student_ID                 | Unique student identifier |
| Study_Hours_per_Week       | Weekly study hours        |
| Past_Exam_Scores           | Previous exam scores      |
| Parental_Education_Level   | Parents education level   |
| Internet_Access_at_Home    | Internet availability     |
| Extracurricular_Activities | Participation status      |
| Final_Exam_Score           | Final examination marks   |
| Pass_Fail                  | Target variable           |

---

# Project Workflow

## 1. Data Collection

* Load dataset from Kaggle
* Understand dataset structure
* Identify numerical and categorical features

## 2. Data Preprocessing

* Handle missing values
* Remove duplicate records
* Encode categorical variables
* Remove unnecessary columns
* Scale numerical data

## 3. Exploratory Data Analysis (EDA)

* Study Hours Analysis
* Attendance Analysis
* Gender-wise Analysis
* Pass vs Fail Distribution
* Correlation Analysis

## 4. Data Visualization

The project includes:

* Bar Charts
* Histograms
* Scatter Plots
* Box Plots
* Heatmaps

## 5. Risk Analysis

Students are classified into:

* High Risk
* Medium Risk
* Low Risk

based on:

* Attendance
* Study Hours
* Past Exam Scores

## 6. Machine Learning Model

* Logistic Regression algorithm
* Train-Test Split
* Feature Scaling
* Prediction of Pass/Fail outcomes

## 7. Model Evaluation

Evaluation metrics used:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC-AUC Score

## 8. Dashboard Creation

Interactive dashboard developed using Streamlit with:

* Dynamic charts
* Filters
* Performance analysis
* Risk category visualization

---

# Visualizations Included

* Pass vs Fail Distribution
* Study Hours Distribution
* Previous Exam Score Distribution
* Study Hours vs Previous exam Score
* Outlier Detection: Previous Exam Score
* Correlation Heatmap
* Confusion Matrix

---

<img width="707" height="605" alt="image" src="https://github.com/user-attachments/assets/1b5f6c40-0032-44ff-a1c2-5a447ed0c559" />


<img width="888" height="607" alt="image" src="https://github.com/user-attachments/assets/d0287676-8413-41b3-8632-62068ad6fcc6" />



<img width="897" height="607" alt="image" src="https://github.com/user-attachments/assets/43e10fc4-aa48-4255-8082-729a25493ae0" />


<img width="928" height="617" alt="image" src="https://github.com/user-attachments/assets/0e8cbd97-c170-45ae-ae62-eb18edf5fe16" />


<img width="895" height="550" alt="image" src="https://github.com/user-attachments/assets/a018bc17-6498-48d9-b873-b6bfb9a4a17d" />


<img width="972" height="871" alt="image" src="https://github.com/user-attachments/assets/01dc64f1-29ba-49fb-a0b3-595014b9e1e8" />


<img width="650" height="593" alt="image" src="https://github.com/user-attachments/assets/ce64afbe-e799-492b-aaef-752fb1ca066e" />



# Machine Learning Algorithm

## Logistic Regression

Logistic Regression is used for binary classification problems. In this project, it predicts whether a student will:

* Pass
* Fail

based on academic and personal performance indicators.

---

# Expected Outcome

The system helps educational institutions:

* Predict student performance
* Identify at-risk students early
* Improve academic support strategies
* Enhance overall student success rates

---

# Installation

## Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly streamlit
```

---

# Run the Project

## Execute Python File

```bash
python student_exam_prediction.py
```

## Run Streamlit Dashboard

```bash
streamlit run app.py
```

---

# Project Structure

```bash
Student-Exam-Pass-Prediction/
│
├── student_exam_prediction.py
├── app.py
├── cleaned_student_data.csv
├── README.md
└── dataset.csv
```

---

# Future Enhancements

* Add more Machine Learning algorithms
* Improve prediction accuracy
* Deploy using Flask or Django
* Add real-time student monitoring
* Integrate cloud database support

---

# Conclusion

The Student Exam Pass Prediction System provides a smart and efficient way to analyze academic performance and predict student outcomes. 
Using Machine Learning and data visualization techniques, institutions can identify struggling students early and take necessary actions to improve 
academic performance and student success.

---
