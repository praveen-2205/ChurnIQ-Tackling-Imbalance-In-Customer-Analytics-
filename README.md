# 📈📈ChurnIQ- Tackling Imbalance in Customer Analytics

### 🚀 This project focuses on predicting customer churn using machine learning models and addresses the challenges posed by imbalanced datasets. So here we solved this problem by **Resampling** in four ways.
####   i) Under Sampling
####  ii) Over Sampling
#### iii) Smote
####  iv) Use of Ensemble with Undersampling
---
## Intially the F1 score was-
## 0: 0.84, 1: 0.58

## After Resampling-
|       Resampling Method       |     F1 Scores    |
|-------------------------------|------------------|
|        Under Sampling         | 0: 0.75, 1: 0.76 |
|        Over Sampling          | 0: 0.77, 1: 0.79 |
|        SMOTE                  | 0: 0.81, 1: 0.79 |
|  Ensemble With Undersampling  | 0: 0.78, 1: 0.60 |

### So here we can find that the F1 score is increased to a very good extent using SMOTE resampling method.

Below is an overview of the steps and methodologies implemented in the project:

## 📝 Project Overview

Customer churn refers to the phenomenon where customers stop doing business with a company. Accurately predicting churn allows businesses to take proactive measures to retain customers. This project employs machine learning techniques to predict churn and handles the inherent class imbalance in churn datasets.

## 📋 Steps in the Notebook

### 1. 🔍 Data Preprocessing
- **Loading Data**: Data is imported and inspected for anomalies.
- **Cleaning Data**: Missing values and inconsistencies are addressed.
- **Feature Engineering**: New features are derived to enhance model performance.
- **Scaling and Encoding**: Numerical features are scaled, and categorical features are encoded.

### 2. 📊 Exploratory Data Analysis (EDA)
- Visualizations and statistical summaries are used to:
  - Understand data distributions.
  - Identify correlations between features.
  - Detect patterns related to customer churn.

### 3. ⚖️ Handling Imbalanced Data
- Techniques implemented to manage the imbalance between churned and non-churned classes:
  - **Oversampling**
  - **Undersampling**
  - **SMOTE**
  - **Ensemble with Undersampling**

### 4. 🤖 Model Building and Evaluation
- While the notebook sets up the foundation for model training, specific implementations of models such as Logistic Regression, Decision Trees, Random Forests, or Gradient Boosting are not included in the current version.
- **Evaluation Metrics** (planned for implementation):
  - Accuracy
  - Precision, Recall, and F1 Score
  - Confusion Matrix

### 5. 🔍 Model Interpretation
- Feature importance analysis is planned to identify key drivers of churn.

## 🏆 Results
- The notebook focuses on preparing data and handling imbalance. Model implementation and results are suggested for future enhancements.

## Language Used
- Python
  
## 🛠️ Libraries Used
- Pandas
- NumPy
- Scikit-learn
- Tensorflow
- Imblearn for Smote
- Matplotlib
- Seaborn

## 🎯 Conclusion
This project serves as a comprehensive guide to tackling customer churn prediction with a special emphasis on handling imbalanced datasets. The techniques and models showcased can be adapted to similar classification problems in different domains.

## 👋 Reach Out
If any doubt or clarification reach me through
- [LinkedIn](www.linkedin.com/in/spraveenkumar2205)
- [E-mail](spraveenkumar2205@gmail.com)
