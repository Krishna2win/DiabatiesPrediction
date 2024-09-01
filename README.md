# Diabetes Prediction

Welcome to the Diabetes Prediction project! This repository contains code and resources for predicting diabetes risk based on various health metrics using machine learning techniques.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling](#modeling)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

The Diabetes Prediction project aims to predict the likelihood of diabetes based on various health-related features. The goal is to create a model that can help identify individuals at risk of diabetes, enabling early intervention and management.

## Features

- **Data Preprocessing**: Cleaning and preparing data for modeling, including handling missing values and feature scaling.
- **Exploratory Data Analysis (EDA)**: Visualizing data to understand relationships between features and the target variable.
- **Modeling**: Training and evaluating machine learning models to identify the best-performing one.
- **Prediction**: Making predictions on new health data.

## Dataset

The dataset used in this project is sourced from [mention the source if applicable]. It includes the following features:

- **Pregnancies**: Number of pregnancies.
- **Glucose**: Plasma glucose concentration.
- **BloodPressure**: Blood pressure (mm Hg).
- **SkinThickness**: Skin thickness (mm).
- **Insulin**: Insulin level (mu U/ml).
- **BMI**: Body mass index.
- **DiabetesPedigreeFunction**: Diabetes pedigree function.
- **Age**: Age of the patient.
- **Outcome**: Whether the patient has diabetes (1) or not (0).

## Installation

To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/Krishna2win/DiabatiesPrediction.git
   cd DiabatiesPrediction
2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
3. Install the required packages:
   ```bash
   pip install -r requirements.txt

## Usage

After installation, you can run the Jupyter notebooks provided to explore the data, train models, and make predictions. The main notebook for the project is `Diabetes_Prediction.ipynb`.

To start the Jupyter notebook server, run:
    ```bash
    jupyter notebook

Open the Diabetes_Prediction.ipynb notebook and follow the instructions to run the cells.

## Modeling

The project explores various machine learning models, including:

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**

The best model is selected based on performance metrics such as Accuracy, Precision, Recall, and F1-Score.

## Results

The final model achieved the following performance metrics:

- **Logistic Regression**: Accuracy of 77.4%, Precision of 0.77, Recall of 0.70, F1-Score of 0.73.

The Logistic Regression was selected as the best model due to its superior performance across these metrics.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

Please make sure to follow the coding style and include tests for any new features or changes.
