# EduMetrics Explorer

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Feature Selection](#feature-selection)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Key Findings](#key-findings)
- [Conclusion](#conclusion)


## Introduction
EduMetrics Explorer is a comprehensive tool designed to analyze and predict student performance. The project utilizes machine learning techniques to provide insights into the factors that influence academic success and to predict student grades based on various features.

## Dataset
The dataset used in this project includes multiple features related to students' academic and personal backgrounds. Key features include:
- Student demographics
- Academic performance records
- Attendance
- Parental involvement
- Study habits

## Preprocessing
Data preprocessing steps include:
1. Handling missing values
2. Encoding categorical variables
3. Scaling numerical features

## Feature Selection
Feature selection was performed to identify the most influential features for predicting student performance. The key features identified are:
- Absences: Regular attendance in class is crucial.
- Study Time Weekly: Consistently studying the material taught in class enhances performance.
- Parental Support: The involvement of parents in a student's academic endeavors significantly predicts success.

## Modeling
A Support Vector Machine (SVM) model was used to predict student grades. The model was trained using all available features and then with a reduced set of key features to compare performance.

## Evaluation
The model's performance was evaluated using accuracy as the metric. The accuracy achieved with all features was 74.5%, while using only the key features resulted in an accuracy of 68.9%.

## Key Findings
- Regular attendance and consistent study habits are critical for academic success.
- Parental support plays a significant role in predicting student performance.
- Using all features provides a more accurate model but requires more computational resources.
- A simplified model with key features is easier to manage with a slight trade-off in accuracy.

## Conclusion
**Key Observations:**
- A Support Vector Machine (SVM) model predicts student grades with an accuracy of 74.5% on the test set using all available features.
- When the dimensionality of the data is reduced to just three features, the model's accuracy drops to 68.9%.

**Important Insights for Students:**
- Attending classes regularly and studying consistently are within the control of students and are critical for achieving good grades.
- Parental support, although beyond the control of students, plays a significant role in academic success.
- By understanding and leveraging these key factors, students can improve their academic performance effectively.

