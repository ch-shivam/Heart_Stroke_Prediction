# Stroke Prediction Project

## Description

This project aims to predict the likelihood of a stroke based on various health and lifestyle factors. It uses machine learning models trained on a dataset of patient information to identify individuals at risk of stroke.

## Dataset

The dataset used for this project is "heart_disease_data.csv". It contains information about various patient attributes, including gender, age, hypertension, heart disease, marital status, work type, residence type, average glucose level, BMI, smoking status, and stroke history.

**Data Source:** [https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset]

**Data Dictionary:**

| Feature          | Description                                     |
|-------------------|------------------------------------------------|
| id               | Unique identifier for each patient              |
| gender           | Gender of the patient (Male, Female, Other)     |
| age              | Age of the patient in years                     |
| hypertension     | Whether the patient has hypertension (0 or 1)   |
| heart_disease    | Whether the patient has heart disease (0 or 1)  |
| ever_married     | Whether the patient has ever been married(0 or 1)|
| work_type        | Type of work the patient does                  |
| Residence_type   | Type of residence (Urban or Rural)  (0 or 1)   |
| avg_glucose_level| Average glucose level in the blood             |
| bmi              | Body Mass Index                                |
| smoking_status   | Smoking status of the patient    (0 or 1 or 2) |
| stroke           | Whether the patient had a stroke (0 or 1)      |

## Methodology

1. **Data Preprocessing:**
   - Handling missing values
   - Converting categorical features to numerical using encoding
   - Scaling numerical features using StandardScaler
   - Balancing classes using SMOTE

2. **Model Training and Evaluation:**
   - Decision Tree Classifier
   - Logistic Regression Classifier
   - K-Nearest Neighbors Classifier
   - Artificial Neural Network (ANN)
   - Evaluation metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix

3. **Prediction:**
   - A function `predict_with_models` is provided to predict stroke risk for new input data.

## Results

[Provide a summary of the results obtained from different models, including their evaluation metrics.]

## Dependencies

-   Python 3.x
-   pandas
-   NumPy
-   scikit-learn
-   imblearn
-   matplotlib
-   seaborn
-   mlxtend
