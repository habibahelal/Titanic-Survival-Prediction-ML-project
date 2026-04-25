
# Titanic Survival Prediction

A machine learning classification project that predicts passenger survival on the Titanic using structured passenger data. The project covers the full machine learning workflow, including exploratory data analysis, preprocessing, model training, hyperparameter tuning, evaluation, and neural network experimentation.

---

## Project Overview

This project aims to predict whether a passenger survived the Titanic disaster based on features such as passenger class, gender, age, fare, family members onboard, and embarkation port.

Multiple machine learning models were trained and compared to identify the best-performing approach. A bonus Artificial Neural Network model was also implemented to explore deep learning performance on tabular data.

---

## Objectives

- Analyze Titanic passenger data and identify survival patterns
- Clean and preprocess structured data for machine learning
- Train and compare multiple classification models
- Improve model performance using hyperparameter tuning
- Evaluate models using reliable classification metrics
- Generate survival predictions for unseen passenger data

---

## Dataset

The project uses Titanic passenger datasets in CSV format:

```text
titanic.csv
test.csv
````

Main features include:

```text
Passenger class
Sex
Age
Fare
Siblings/spouses aboard
Parents/children aboard
Embarkation port
Survival status
```

---

## Technologies Used

```text
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
SciPy
TensorFlow / Keras
Jupyter Notebook
```

---

## Machine Learning Workflow

### 1. Data Exploration

Performed exploratory data analysis to understand:

* Data structure and feature types
* Missing values
* Duplicate records
* Survival distribution
* Relationships between passenger features and survival
* Correlations between numerical variables

### 2. Data Preprocessing

Prepared the dataset for modeling by applying:

* Missing value handling
* Categorical feature encoding
* Feature selection
* Outlier detection using Z-score
* Train-test splitting

### 3. Model Training

The following models were implemented and compared:

* Gaussian Naive Bayes
* K-Nearest Neighbors
* Support Vector Machine
* Artificial Neural Network

### 4. Model Optimization

Model performance was improved using:

* Cross-validation
* GridSearchCV
* Kernel tuning for SVM
* Distance metric comparison for KNN
* Early stopping for the neural network

### 5. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Classification report
* Confusion matrix
* Cross-validation score

---

## Best Performing Model

The tuned Support Vector Machine model achieved the strongest performance among the traditional machine learning models.

The Artificial Neural Network was also tested as an additional deep learning approach and used to generate predictions on unseen test data.

---

## Project Structure

```text
titanic-survival-prediction/
│
├── titanic-survival-prediction-ml-ann.ipynb
├── titanic.csv
├── test.csv
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/titanic-survival-prediction.git
cd titanic-survival-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Requirements

Create a `requirements.txt` file with:

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
scipy
tensorflow
keras
jupyter
```

---

## How to Run

Open the notebook:

```bash
jupyter notebook titanic-survival-prediction-ml-ann.ipynb
```

Run all cells from top to bottom.

Make sure the dataset files are in the same directory as the notebook:

```text
titanic.csv
test.csv
```

---

## Key Skills Demonstrated

```text
Data Cleaning
Exploratory Data Analysis
Data Visualization
Feature Engineering
Classification Modeling
Hyperparameter Tuning
Cross-Validation
Neural Networks
Model Evaluation
Prediction on Unseen Data
```

---

## Future Improvements

* Add more advanced feature engineering
* Test ensemble models such as Random Forest and XGBoost
* Save the best model using Pickle or Joblib
* Generate a Kaggle-ready submission file
* Build a Streamlit web app for interactive survival prediction


```
