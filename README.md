# Task4: Classification with Logistic Regression

 **Overview**
 
This repository contains the solution for Task 4 of the Elevate AI & ML Internship.
The objective of this task was to build a binary classifier using Logistic Regression and evaluate it using various performance metrics.

**Dataset**

The Breast Cancer Wisconsin (Diagnostic) Dataset from Kaggle was used to demonstrate binary classification by predicting whether a tumor is benign or malignant based on 30 numerical features.

Target column: diagnosis (M = Malignant, B = Benign)

Samples: 569

 **Tools and Libraries Used**
 
Python 3.x

Pandas – Data handling and preprocessing

Scikit-learn – Logistic Regression model, evaluation metrics

Matplotlib – Data visualization

**Task Steps**

Import and Preprocess the Dataset

Loaded dataset from Kaggle CSV file.

Dropped unnecessary columns (id, Unnamed: 32).

Encoded target column (M → 1, B → 0).

Train-Test Split

Split data into 80% training and 20% testing sets using train_test_split.

Feature Standardization

Applied StandardScaler to normalize features.

Fit the Logistic Regression Model

Trained the model using LogisticRegression from Scikit-learn.

Evaluate the Model

Calculated Confusion Matrix.

Generated Classification Report with precision, recall, and F1-score.

Plotted ROC Curve and calculated AUC score.

Threshold Tuning

Modified decision threshold from the default 0.5 to observe changes in classification performance.

Sigmoid Function Explanation

Plotted the sigmoid function to visualize how Logistic Regression maps values to probabilities.

 **How to Run**
Download the dataset from Kaggle and save it as breast_cancer.csv.

Install required libraries:

pip install pandas numpy matplotlib scikit-learn

Run the Python script:

python logistic_regression_task4.py

**What I Learned**

How Logistic Regression is used for binary classification.

How to preprocess and scale numerical data.

How to evaluate classification models using precision, recall, F1-score, and ROC-AUC.

The effect of adjusting the decision threshold on model predictions.

The role of the sigmoid function in probability estimation.

 **Submission**
 
This repository is submitted as part of the Elevate AI & ML Internship – Task 4.
