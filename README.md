# Student_score_Prediction-
A regression-based machine learning project to predict student exam scores. 🎓 Student Score Prediction — Machine Learning Project

A regression-based machine learning project designed to predict students’ final exam scores based on various study habits and lifestyle factors.

📘 Overview

This project explores how different factors — such as study hours, sleep duration, attendance, and motivation level — influence students’ performance in final exams.

Using the Student Performance Factors Dataset, we clean, visualize, and model the data to find patterns that impact learning outcomes.

🎯 Objectives

🧹 Data Cleaning: Handle missing values and prepare the dataset

📈 Exploratory Data Analysis (EDA): Understand feature relationships using visualizations

🧮 Model Building: Implement Linear and Polynomial Regression

📊 Model Evaluation: Compare performance using MSE and R² metrics

🖼️ Visualization: Display actual vs. predicted exam scores

🧰 Tools & Libraries

Built using Python 3.13, with the following libraries:

pandas, numpy → Data handling & analysis

matplotlib, seaborn → Data visualization

scikit-learn → Model training & evaluation

joblib → Model saving and loading

📊 Model Results Model Mean Squared Error (MSE) R² Score Linear Regression 5.33 0.62 Polynomial (Degree 2) 5.23 0.63 Polynomial (Degree 3) 5.29 0.63

✅ The Polynomial Regression (Degree 2) model slightly outperformed the Linear Regression model, showing that non-linear relationships exist between the features and final exam scores.
