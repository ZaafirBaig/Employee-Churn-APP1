# Employee Churn Prediction

This repository contains a machine learning project designed to predict employee churn using a RandomForest classifier. The project includes data preprocessing, model training, and a Streamlit application for making predictions.

- ## File Descriptions

- **`app.py`**: Contains the Streamlit application code for user interaction and prediction.
- **`pipeline_model.pkl`**: Pickle file of the trained machine learning pipeline.
- **`my_feature_dict.pkl`**: Pickle file containing the feature dictionary used in the application.
- **`requirements.txt`**: Lists all Python packages required to run the project.
- **`Employee.csv`**: Dataset file used in training and testing the model.

## Features

- **Predict Employee Churn**: Use the application to input employee data and predict whether an employee is likely to churn.
- **Categorical and Numerical Feature Handling**: The application handles both categorical and numerical features for prediction.

## Model Training

The model is trained using a RandomForest classifier. The training pipeline includes:
- **Data Preprocessing**: Imputing missing values and scaling numerical features, one-hot encoding categorical features.
- **Feature Engineering**: Transformations applied to both numerical and categorical features.
- **Model Fitting**: Training the RandomForest classifier on the preprocessed data.

## Usage
**Access the application**:
   Open your web browser and go to `(https://employee-churn-predictor.streamlit.app/)`.

