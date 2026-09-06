# Cardiovascular Disease Prediction

An end-to-end machine learning project for predicting cardiovascular disease using patient health data.

## 📌 Project Overview

This project focuses on building and evaluating machine learning classification models to predict whether a patient is likely to have cardiovascular disease based on health-related features.

The project follows a complete machine learning workflow:

- Data loading
- Data exploration
- Data preprocessing
- Categorical feature encoding
- Feature selection
- Train-validation split
- Model training
- Hyperparameter experimentation
- Model evaluation
- Comparison of classification models

## 📊 Dataset

The project uses the `heart.csv` dataset containing patient health information.

The target variable is:

`HeartDisease`

The dataset contains features related to:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak
- ST Slope

Categorical features are converted into numerical representations using one-hot encoding before training the models.

## 🤖 Machine Learning Models

The project experiments with three classification algorithms:

### 1. Decision Tree

A Decision Tree classifier is trained while experimenting with parameters such as:

- `min_samples_split`
- `max_depth`

### 2. Random Forest

A Random Forest classifier is evaluated using different values for:

- `min_samples_split`
- `max_depth`
- `n_estimators`

### 3. XGBoost

An XGBoost classifier is trained with:

- `n_estimators = 500`
- `learning_rate = 0.1`
- Early stopping
- Validation data for evaluation

## 📈 Model Evaluation

The models are evaluated using classification accuracy on the training and validation datasets.

The project also includes experiments that visualize how different hyperparameter values affect training and validation accuracy.

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 📁 Project Structure

```text
cardiovascular_disease_(heart)/
│
├── cardiovascular_disease_(CVDs).ipynb
├── heart.csv
├── requirements.txt
├── README.md
└── .gitignore