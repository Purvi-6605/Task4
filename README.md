# Task4: Classification with Logistic Regression

 **Overview**
 
This repository contains the solution for Task 4 of the Elevate AI & ML Internship.
The objective of this task was to build a binary classifier using Logistic Regression and evaluate it using various performance metrics.

**Dataset**

The Breast Cancer Wisconsin (Diagnostic) Dataset from Kaggle was used to demonstrate binary classification by predicting whether a tumor is benign or malignant based on 30 numerical features.

Target column: diagnosis (M = Malignant, B = Benign)

Samples: 569

 **Tools and Libraries Used**
 
1.Python 3.x

2.Pandas – Data handling and preprocessing

3.Scikit-learn – Logistic Regression model, evaluation metrics

4.Matplotlib – Data visualization

**Task Steps**

1.Import and Preprocess the Dataset

  Loaded dataset from Kaggle CSV file.

  Dropped unnecessary columns (id, Unnamed: 32).

  Encoded target column (M → 1, B → 0).

2.Train-Test Split

  Split data into 80% training and 20% testing sets using train_test_split.

3.Feature Standardization

  Applied StandardScaler to normalize features.

4.Fit the Logistic Regression Model

  Trained the model using LogisticRegression from Scikit-learn.

5.Evaluate the Model

  Calculated Confusion Matrix.

  Generated Classification Report with precision, recall, and F1-score.

  Plotted ROC Curve and calculated AUC score.

6.Threshold Tuning

  Modified decision threshold from the default 0.5 to observe changes in classification performance.

7.Sigmoid Function Explanation

  Plotted the sigmoid function to visualize how Logistic Regression maps values to probabilities.

 **How to Run**
 
1.Download the dataset from Kaggle and save it as breast_cancer.csv.

2.Install required libraries:

   pip install pandas numpy matplotlib scikit-learn

3.Run the Python script:

  python logistic_regression_task4.py

**What I Learned**

How Logistic Regression is used for binary classification.

How to preprocess and scale numerical data.

How to evaluate classification models using precision, recall, F1-score, and ROC-AUC.

The effect of adjusting the decision threshold on model predictions.

The role of the sigmoid function in probability estimation.

 **Submission**
 
This repository is submitted as part of the Elevate AI & ML Internship – Task 4.
