# Student Dropout Prediction

A machine learning project focused on predicting student dropout risk and identifying the key factors associated with student attrition. The project uses an academic dataset to perform exploratory data analysis, data preprocessing, feature engineering, and classification modeling.

## Project Overview

The dataset was analyzed to understand patterns and factors influencing student dropout. Since the dataset contains class imbalance, SMOTE was applied to improve the representation of the minority class before model training.

Multiple classification algorithms were trained and compared, including:

- Logistic Regression
- Decision Tree
- Random Forest

The models were evaluated using accuracy, precision, recall, and F1-score to assess their predictive performance.

The analysis also identified important factors associated with student dropout, including attendance, academic performance, and financial status.

## Key Steps

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Handling class imbalance using SMOTE
- Training classification models
- Hyperparameter tuning
- Model performance evaluation
- Identifying important dropout-related factors

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab
- imbalanced-learn (SMOTE)
