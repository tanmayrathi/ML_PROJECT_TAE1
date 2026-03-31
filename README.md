# ML-PROJECT
# Stroke Prediction using Machine Learning

## Project Overview

This project focuses on predicting the likelihood of a patient having a stroke using various machine learning classification algorithms. The goal is to build models that can analyze patient health data and accurately predict stroke risk.

Stroke prediction is a critical healthcare application where early detection can help in preventing severe medical conditions and saving lives.

## Dataset
The dataset contains medical and demographic information of patients. The target variable indicates whether the patient has had a stroke or not.
Features include:
.Age
.Gender
.Hypertension
.Heart Disease
.Marital Status
.Work Type
.Residence Type
.Average Glucose Level
.Body Mass Index (BMI)
.Smoking Status

Target:
0 → No Stroke
1 → Stroke
## Machine Learning Models Used
70:30-Nupur Bhuradkar
80:20-Tanmay Rathi

The following classification algorithms were implemented and evaluated:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree
4. Random Forest
5. Support Vector Machine (SVM)
6. Naive Bayes
7. Gradient Boosting
8. AdaBoost
9. Extra Trees
10. XGBoost
11. Linear Discriminant Analysis
12. Quadratic Discriminant Analysis

## Tools and Libraries

The project uses the following Python libraries:

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

## Project Workflow

The workflow followed in this project includes:
.Load the stroke dataset
.Handle missing values (especially BMI)
.Encode categorical variables
.Perform exploratory data analysis (EDA)
.Handle class imbalance (if required using SMOTE or undersampling)
.Split dataset into training and testing sets
.Train multiple machine learning models
.Evaluate models using accuracy, precision, recall, and F1-score
.Compare performance of different algorithms

## Objective

The objective of this project is to:
.Predict the probability of stroke occurrence
.Compare different machine learning models
.Understand the impact of health factors on stroke risk
.Build a healthcare-focused ML application

## Results

-Models were trained and evaluated on the dataset
-Due to class imbalance, accuracy alone is not sufficient
-Metrics like Precision, Recall, and F1-score provide better insights
-Ensemble models like Random Forest and Gradient Boosting performed well

## How to Run the Project

1. Clone this repository
2. Install required libraries
3. Run the Python script

Example:

```bash
git clone https://github.com/yourusername/stroke-prediction.git
cd stroke-prediction
python iris_models.py
```

## Applications
*Early stroke risk prediction
*Healthcare decision support systems
*Preventive medical analysis
*Educational machine learning project

## Author
This project was developed as part of learning and applying machine learning techniques in healthcare.

