# Diabetes Prediction System

## Description
The Diabetes Prediction System is a machine learning-based project designed to predict whether a person is diabetic or not based on specific health metrics. The system uses a Support Vector Machine (SVM) model with a linear kernel to classify individuals as diabetic or non-diabetic. The project is implemented in Python and leverages the `diabetes.csv` dataset.

## Dataset
The dataset used in this project is `diabetes.csv`, which contains 768 rows and 9 columns. Each row represents a patient's health data, and the columns include the following features:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function (genetic risk)
- **Age**: Age of the patient
- **Outcome**: Target variable (0 = Non-diabetic, 1 = Diabetic)

## Features
- **Data Preprocessing**: Standardization of input data using `StandardScaler`.
- **Model Training**: SVM model with a linear kernel for classification.
- **Prediction**: Real-time diabetes prediction based on user input.
- **Accuracy Evaluation**: Model accuracy on both training and test datasets.
- **Input Sample Testing**: Allows users to test the model with custom input data.

## Technologies Used
- Python 3.9
- Libraries:
  - `pandas` for data manipulation
  - `numpy` for numerical computations
  - `scikit-learn` for machine learning (SVM, preprocessing, and evaluation)

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
