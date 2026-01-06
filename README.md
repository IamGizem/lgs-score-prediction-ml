# 🎓 LGS Exam Score Prediction Analysis

This project is an end-to-end data science study that predicts student scores for the Turkish High School Entrance Exam (LGS). It covers data generation, exploratory data analysis (EDA), and machine learning implementation.

## 📌 Project Goals
The objective is to understand how various academic and behavioral factors influence a student's final LGS score.

## 📊 Dataset Features
The model uses the following features for prediction:
* **Gender:** Student's gender (Encoded for the model).
* **Absenteeism:** Number of days the student was absent.
* **Weekly_Reading_Hours:** Average hours spent reading books per week.
* **Exam_Average:** Mean score from mock exams throughout the year.
* **Math_Score:** Net score from the mathematics section (Key feature).

## 🚀 Technical Implementation
1. **Preprocessing:** Categorical variables were converted to numerical values using `LabelEncoder`.
2. **Train-Test Split:** The data was split into 80% training and 20% testing sets.
3. **Model:** A **Linear Regression** algorithm was trained to predict the continuous `LGS_Score`.

## 💡 Key Insights & Results
* **Mathematics is King:** The model assigned the highest coefficient (approx. 5.25) to `Math_Score`, confirming its critical role in the exam.
* **Impact of Attendance:** `Absenteeism` showed a clear negative correlation with success.
* **Model Accuracy:** The R-Squared ($R^2$) score is approximately **0.99**, indicating a very strong fit for the synthetic dataset.

## 🛠 Libraries Used
* **Pandas & Numpy:** Data manipulation.
* **Matplotlib & Seaborn:** Data visualization.
* **Scikit-Learn:** Machine learning and metrics.

---
*Created by Data Analyst Gizem Eroglu*
