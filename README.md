# Adult Income ML Pipeline

## Project Overview

This project presents a complete Machine Learning workflow using the Adult Income Dataset. The objective is to explore the factors that influence annual income, build preprocessing pipelines, develop regression and classification models, and evaluate their performance using appropriate metrics.

The project demonstrates the practical application of Exploratory Data Analysis (EDA), feature engineering, Scikit-Learn Pipelines, model evaluation, and hyperparameter tuning.

---

## Dataset

The Adult Income Dataset contains demographic and employment-related information about individuals and is commonly used for income prediction tasks.

### Main Targets

1. **Regression Task**

   * Predict `hours-per-week`

2. **Classification Task**

   * Predict whether an individual's annual income exceeds `$50K`

---

## Project Tasks

### Question 1: Exploratory Data Analysis (EDA)

Performed exploratory data analysis to identify the most important factors affecting annual income.

#### Objectives

* Conduct descriptive statistical analysis
* Visualize feature distributions and relationships
* Identify the top three factors influencing income
* Provide intuitive explanations for feature importance

#### Key Findings

Top income-related factors identified through visual and statistical analysis:

1. Education Level
2. Occupation
3. Capital Gain

---

### Question 2: Preprocessing Pipeline Design

Designed reusable Scikit-Learn preprocessing pipelines to prepare data for machine learning models.

#### Preprocessing Steps

##### Numerical Features

* Missing Value Imputation (Median)
* Feature Scaling (StandardScaler)

##### Categorical Features

* Missing Value Imputation (Most Frequent)
* One-Hot Encoding

#### Technologies Used

* Pipeline
* ColumnTransformer
* SimpleImputer
* StandardScaler
* OneHotEncoder

---

### Question 3: Regression Modeling & Evaluation

Built and evaluated regression models to predict `hours-per-week`.

#### Models

* Linear Regression
* SGD Regressor

#### Evaluation Metrics

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

#### Outcome

Model performances were compared to determine which algorithm generalized better on unseen data.

---

### Question 4: Classification Pipeline & Error Analysis

Built an end-to-end classification pipeline using Logistic Regression to predict income level.

#### Model

* Logistic Regression

#### Evaluation Metrics

* Accuracy
* Precision
* Recall

#### Pipeline Components

* Missing Value Handling
* Feature Encoding
* Feature Scaling
* Logistic Regression Classifier

---

### Question 5: Hyperparameter Tuning & Model Comparison

Implemented and optimized a K-Nearest Neighbors (KNN) classifier.

#### Hyperparameter Tuning

* GridSearchCV
* Number of Neighbors (K)
* Distance Metrics

  * Manhattan Distance
  * Euclidean Distance
* Weighting Strategies

#### Model Comparison

Compared:

* Logistic Regression
* Tuned KNN Classifier

#### Conclusion

The tuned KNN model showed slightly better performance than the default Logistic Regression model on the sampled dataset. Since KNN often benefits from larger training datasets, it is expected that the tuned model could achieve even better results when trained on the complete dataset.

---

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Machine Learning Concepts Demonstrated

* Exploratory Data Analysis (EDA)
* Feature Selection
* Data Cleaning
* Missing Value Handling
* Feature Encoding
* Feature Scaling
* Scikit-Learn Pipelines
* Regression Modeling
* Classification Modeling
* Hyperparameter Tuning
* Model Evaluation
* Grid Search Cross Validation

---

## Author

S M Anik Hasan

Machine Learning & Data Science Enthusiast
