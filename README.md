# E-commerce-product-buyer-session-prediction

Objective
---
Predict whether customer purchase a product or not in a session

Data Summary
---
The datasets contain following files

- `train.dat`: 4072954 rows X 5 columns, 1125000 session_ids
- `test.dat`: 1040614 rows X 4 columns, 306825 session_ids
- `sample_submission.csv` - 100X2 (session_id, label columns)

**Columns Summary**

- `session_id` : Represent the unique session a user interected with products and category(s)
- `timestamp` : timestamp
- `category`: category of items, the user interected within that session(could be one or more)
- `item_id_code`: Unique code for each product
- `label`: Target outcome to predict - whether user purchased in that session or not.

Contents
---

- [Problem Statement](#problem-statement)
- [Data Summary](#data-summary)
- [Approach Overview](#approach-overview)
- [Installation](#installations)
- [Imports](#imports)
- [Data Loader](#data-loader)
- [Exploratory Data Analysis(EDA)](#exploratory-data-analysis(EDA))
- [Feature Engineering/Extraction](#feature-engineeringextraction)
- [Feature Encoding](#feature-encoding)
- [Feature Selection](#feature-selection)
- [Modeling](#modeling)
- [Model Evaluation/Selection](#model-evaluationselection)
- [Hyper-parameter Tuning](#models-hyper-parameter-tuning)
- [Prediction Over Test Set](#predictions-over-test-set)
- [Neural Network based Modeling](#multilayer-perceptron-model)
    - [Data Preparation](#data-preparation)
    - [Train/Valid Split](#trainvalid-split)
    - [Model Building](#model-building)
    - [Model's Evaluation](#models-evaluation)
    - [Model's Inference](#models-inference)


