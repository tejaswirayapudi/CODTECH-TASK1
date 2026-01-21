 NAME : RAYAPUDI LAKSHMI TEJASWI
 
COMPANY : CODESOFT IT SOLUTIONS

ID : BY25RY257716

DURATION : JAN 2026

DOMAIN : Data Science



Task 1 Overview: Titanic Survival Prediction

Objective

The primary goal of this task was to develop a machine learning model to predict whether a passenger survived the Titanic disaster based on available passenger data. This binary classification problem aimed to explore patterns in survival rates influenced by factors such as age, gender, ticket class, and fare, while demonstrating core data science skills in preprocessing, modeling, and evaluation.


Key Activities

•  Data Exploration and Analysis (EDA): Loaded the Titanic dataset using Seaborn, examined structure (head, shape, columns), identified missing values (e.g., age, embarked), and visualized survival distributions and correlations (e.g., survival by gender and class).

•  Data Preprocessing: Selected relevant features (pclass, sex, age, sibsp, parch, fare, embarked), handled missing values with imputation (median for numerical, most frequent for categorical), and encoded categorical variables using OneHotEncoder.

•  Model Building and Training: Implemented a Random Forest Classifier within a scikit-learn Pipeline for seamless preprocessing and modeling, with train-test split (stratified for balance).
•  Model Evaluation: Calculated accuracy (~81-83%), generated classification report (precision, recall, F1-score), visualized confusion matrix, and analyzed feature importances (highlighting sex, fare, and age as top predictors).

•  Insights and Validation: Interpreted results aligning with historical facts (e.g., higher survival for women and first-class passengers) and tested predictions on sample data.



Technologies Used

•  Programming Language: Python

•  Libraries: Pandas (data manipulation), NumPy (numerical operations), Seaborn & Matplotlib (visualization), scikit-learn (preprocessing, modeling, evaluation with Pipeline, ColumnTransformer, SimpleImputer, OneHotEncoder, RandomForestClassifier, metrics)

•  Environment: Jupyter Notebook for interactive development and documentation

This task provided hands-on experience in end-to-end machine learning workflows, from data cleaning to insightful model interpretation. It reinforced best practices in handling real-world datasets with missing values and categorical features.

