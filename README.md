# Iris Flower Species Classification

This repository contains a machine learning project that classifies Iris flowers into three species: **Setosa, Versicolor, and Virginica**. The project implements a rigorous data science workflow, including data preprocessing, feature scaling, and comparative analysis of multiple classification models.

## 🛠️ Features
* **Data Preprocessing**: Label encoding for target classes and feature scaling using `StandardScaler`.
* **Multiple Models**: Implementation and comparison of:
    * Logistic Regression
    * Gaussian Naive Bayes
    * K-Nearest Neighbors (KNN)
* **Optimization**: Hyperparameter tuning using `GridSearchCV` to find the best `n_neighbors` for KNN.
* **Pipelines**: Use of Scikit-Learn `Pipeline` to prevent data leakage and streamline the training process.



## 📊 Dataset
The project uses the classic **Iris Dataset**, which includes 150 samples with four features:
1. Sepal Length (cm)
2. Sepal Width (cm)
3. Petal Length (cm)
4. Petal Width (cm)

## 💻 Tech Stack
* **Language**: Python 3.x
* **Libraries**: Pandas, Scikit-Learn

## 📈 Methodology & Results

### 1. Data Cleaning
The `Id` column was removed as it does not contribute to predictive power. The `Species` column was transformed from text to numerical format using `LabelEncoder`.

### 2. Model Performance
After splitting the data into training (80%) and testing (20%) sets, the models achieved the following accuracy:

| Model | Accuracy |
| :--- | :--- |
| Logistic Regression | 100% |
| Gaussian Naive Bayes | 100% |
| Optimized KNN | 100% |

> **Note**: The 100% accuracy reflects the high separability of the Iris dataset features
