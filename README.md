# Heart-disease-prediction
Heart Disease Prediction is a machine learning project that predicts whether a person may have heart disease using health-related factors such as age, blood pressure, cholesterol, heart rate, and chest pain. It uses the Logistic Regression algorithm for classification.

# Heart Disease Prediction

## Overview

Heart Disease Prediction is a machine learning project that predicts whether a person may have heart disease based on different health-related features. The project uses Python, data preprocessing, and Logistic Regression to classify the results.

## Objectives

* Analyze heart disease data.
* Clean and prepare the dataset.
* Identify important health-related features.
* Train a machine learning classification model.
* Predict heart disease outcomes.
* Evaluate the model performance.

## Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

## Dataset Features

The dataset contains:

* Age
* Sex
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Maximum Heart Rate
* Chest Pain Type
* Oldpeak
* Resting ECG
* Exercise Angina
* ST Slope
* Heart Disease

### Target Variable

* `0` = No Heart Disease
* `1` = Heart Disease

## Data Preprocessing

The project performs the following steps:

1. Loads the dataset using Pandas.
2. Checks for missing values.
3. Fills missing numerical values using the median.
4. Separates input features and the target variable.
5. Splits the data into training and testing sets.
6. Standardizes the features using StandardScaler.

## Machine Learning Algorithm

The project uses **Logistic Regression** for binary classification. The model predicts whether the given health information is classified as heart disease or no heart disease.

## Model Evaluation

The model is evaluated using:

* Accuracy
* Classification Report
* Confusion Matrix

## Example Prediction

The project provides sample health information for a new person and uses the trained model to predict whether the person is classified as having heart disease or no heart disease.

## Visualization

A scatter plot is created to show the relationship between **age and cholesterol** based on the heart disease outcome.

The visualization is saved as:

```text
heart_disease_analysis.png
```

## Project Structure

```text
Heart_Disease_Prediction/
│
├── README.md
├── heart_disease_prediction.py
├── heart_disease.csv
└── requirements.txt
```

## How to Run

### 1. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 2. Run the Program

```bash
python heart_disease_prediction.py
```

## Output

The program displays:

* First five rows of the dataset
* Dataset shape
* Missing value information
* Model accuracy
* Classification report
* Confusion matrix
* Example prediction

It also generates a visualization for heart disease feature analysis.

## Applications

This type of project can be used for educational purposes to:

* Analyze health-related datasets.
* Understand machine learning classification.
* Identify patterns in heart disease data.
* Demonstrate the use of Logistic Regression.

## Important Note

This is an educational machine learning project using a classroom dataset. It is not a medical diagnostic tool and should not be used for clinical or medical decisions.

## Conclusion

The Heart Disease Prediction project demonstrates how machine learning can be used to classify heart disease outcomes. It combines data preprocessing, Logistic Regression, model evaluation, and visualization to create a complete machine learning project.
