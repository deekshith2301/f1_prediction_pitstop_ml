🏎️ F1 Pit Stop Prediction using Machine Learning
📌 Project Overview

This project predicts whether a Formula 1 driver will make a pit stop on the next lap using machine learning. It is based on an F1 racing dataset from Kaggle and treats the task as a binary classification problem:

0 → Driver will not pit on the next lap
1 → Driver will pit on the next lap

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, experiment tracking with MLflow, and Kaggle submission.

Objective:

Build a machine learning model that predicts whether a driver will enter the pit lane on the following lap based on race conditions and driver-related features.

Dataset:
Source: Kaggle F1 Pit Stop Prediction Dataset
Target Variable: PitNextLap

Due to GitHub file size limitations, the dataset is not included in this repository. Please download it directly from Kaggle.

 Exploratory Data Analysis (EDA)

Performed:

Missing value analysis
Outlier detection
Class imbalance analysis
Correlation analysis
Feature distribution analysis
Feature importance exploration

 Data Preprocessing:
Removed unnecessary columns
Handled categorical variables
One-Hot Encoding
Feature scaling (where required)
Train/Test split
 Models Implemented
Logistic Regression
Linear SVC
Random Forest
XGBoost
Experiment Tracking

Used MLflow to:
Track multiple experiments
Compare model performance
Store evaluation metrics
Save trained models
📊 Evaluation Metrics

The following metrics were used:

Accuracy
Precision
Recall
F1 Score
🏆 Kaggle Result

Best Public Score: 0.81684

The best-performing model was selected using MLflow and used for generating the Kaggle submission.
<img width="959" height="443" alt="image" src="https://github.com/user-attachments/assets/0e7ea896-059a-416f-afc8-93e71b430b48" />
<img width="957" height="446" alt="image" src="https://github.com/user-attachments/assets/3c9870dd-c481-4e3d-8759-400905aa38f8" />
<img width="752" height="375" alt="image" src="https://github.com/user-attachments/assets/52d3906a-feed-4b87-b86c-35a1e26489af" />


