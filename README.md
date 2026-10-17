# Heart Disease Prediction - Classification Challenge

## Introduction
This project aims to predict the presence of heart disease in patients using machine learning classification models based on various health indicators (cholesterol, blood pressure, age, etc.).

## How to Run
1. Open `heart_disease.ipynb` in Jupyter Notebook.
2. Run all cells sequentially to execute data loading, scaling, visualizations, model training, and evaluation.

## Libraries & Functions Used
- **Pandas & NumPy**: For data manipulation.
- **Seaborn & Matplotlib**: For data visualization (count plots and correlation heatmaps).
- **Scikit-Learn**: 
  - `StandardScaler` for feature scaling.
  - `LogisticRegression`, `GaussianNB`, `KNeighborsClassifier` for classification.
  - `accuracy_score`, `classification_report`, `confusion_matrix` for model evaluation.

## Model Evaluation & Comparison
Three models were trained and compared:
1. **Logistic Regression**: Linear model effective for binary classification.
2. **Naive Bayes (GaussianNB)**: Probabilistic classifier based on Bayes' theorem.
3. **K-Nearest Neighbors (KNN)**: Instance-based learning algorithm.

### Results:
- **Logistic Regression Accuracy:** ~85%
- **Naive Bayes Accuracy:** ~83%
- **KNN Accuracy:** ~82%

Detailed metrics (`confusion_matrix` and `classification_report`) for each model are outputted inside the Jupyter Notebook.
