# Breast-canser-Supervised-Learning-Algoritham
Breast canser Prediction using Logistic Regression,Decision Tree classifier,Random Forest Classifier,SVM and KNN
## Objective
The objective of this project is to evaluate understanding and application of supervised learning techniques using the Breast Cancer dataset from sklearn. The project focuses on implementing various classification algorithms and comparing their performance.

## Dataset
The Breast Cancer dataset is sourced from sklearn, containing:
- **569 instances** 
- **30 features** that describe various characteristics of the tumors.

## Key Components

### 1. Loading and Preprocessing
- **Data Loading**: The dataset is loaded using `sklearn.datasets.load_breast_cancer()`.
- **Missing Values**: No missing values were found in the dataset.
- **Feature Scaling**: StandardScaler is used to scale the features to ensure they have a mean of 0 and a standard deviation of 1, which helps improve the performance of the classification algorithms.

### 2. Classification Algorithms
The following classification algorithms were implemented:
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**
- **k-Nearest Neighbors (k-NN)**

### 3. Model Comparison
Each model's performance is evaluated using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

### Results
- **Best Model**: Random Forest achieved the highest performance metrics.
- **Worst Model**: Decision Tree had the lowest performance among the evaluated models.

### Performance Summary
All models performed well overall. Logistic Regression, Decision Tree, Random Forest, and SVM achieved perfect scores in several metrics, making them the top choices for this dataset. k-NN performed slightly lower but remained effective.

## Conclusion
This project demonstrates the effectiveness of supervised learning techniques in classifying breast cancer instances based on various tumor characteristics. The Random Forest model emerged as the most reliable classifier for this dataset.

