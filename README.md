# E-commerce Product Buyer Session Prediction 🛒🔮

## Objective
The objective of this project is to predict whether a customer will purchase a product in a session based on their interactions with various items and categories.

## Data Summary 📊
The dataset consists of the following files:

- `train.dat`: 4,072,954 rows x 5 columns, with 1,125,000 session_ids
- `test.dat`: 1,040,614 rows x 4 columns, with 306,825 session_ids
- `sample_submission.csv`: 100 rows x 2 columns (session_id, label)

### Columns Summary:
- `session_id`: Unique identifier for each user session
- `timestamp`: Timestamp of the session
- `category`: Category of items the user interacted with during the session (could be one or more)
- `item_id_code`: Unique code for each product
- `label`: Target outcome to predict - whether the user purchased in that session or not

## Contents 📝
- **[Problem Statement](#problem-statement)**
- **[Data Summary](#data-summary)**
- **[Approach Overview](#approach-overview)**
- **[Installation](#installations)**
- **[Imports](#imports)**
- **[Data Loader](#data-loader)**
- **[Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)**
- **[Feature Engineering/Extraction](#feature-engineeringextraction)**
- **[Feature Encoding](#feature-encoding)**
- **[Feature Selection](#feature-selection)**
- **[Modeling](#modeling)**
- **[Model Evaluation/Selection](#model-evaluationselection)**
- **[Hyper-parameter Tuning](#models-hyper-parameter-tuning)**
- **[Prediction Over Test Set](#predictions-over-test-set)**
- **[Neural Network based Modeling](#multilayer-perceptron-model)**
    - **[Data Preparation](#data-preparation)**
    - **[Train/Valid Split](#trainvalid-split)**
    - **[Model Building](#model-building)**
    - **[Model's Evaluation](#models-evaluation)**
    - **[Model's Inference](#models-inference)**

## Approach Overview 📋
This project involves preprocessing the data, conducting exploratory data analysis, engineering relevant features, encoding categorical variables, selecting appropriate features, modeling, evaluating and selecting the best performing model, tuning hyperparameters, and finally making predictions over the test set. Additionally, a neural network-based approach using Multilayer Perceptron (MLP) is also explored for prediction.
