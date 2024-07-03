# Titanic Kaggle Competition

This repository contains the code and documentation for my participation in the Titanic Kaggle Competition. The goal is to predict the survival of passengers on the Titanic based on various features such as age, gender, class, etc.

![sap](https://github.com/Hammad112/Titanic-Survival-Predictor/assets/95902997/3056f73e-d2db-4937-89b7-9afe7a341601)

![asasas](https://github.com/Hammad112/Titanic-Survival-Predictor/assets/95902997/59df88ef-a395-4903-bb02-601d39f7dc6d)

## Usage

Follow these steps to run the project:

1. **Data Preprocessing and Missing Values Handling**:
   - The script `data_preprocessing.py` handles missing values and preprocesses the data.
   - Run it using:
     ```bash
     python data_preprocessing.py
     ```

2. **Exploratory Data Analysis (EDA)**:
   - The notebook `eda.ipynb` contains the exploratory data analysis.
   - Open it in Jupyter Notebook or Jupyter Lab and run the cells to see the analysis.

3. **Model Training**:
   - The script `train_model.py` is used to train the model.
   - Run it using:
     ```bash
     python train_model.py
     ```

4. **Model Predictions**:
   - The script `predict_model.py` is used to make predictions on the test data.
   - Run it using:
     ```bash
     python predict_model.py
     ```

## Features

- Handling missing values
- Exploratory Data Analysis (EDA)
- Model training using various machine learning algorithms
- Generating predictions for the test dataset

## Exploratory Data Analysis (EDA)

The EDA notebook (`eda.ipynb`) includes:

- Visualization of the distribution of features
- Correlation analysis
- Insights and findings from the data

## Model Training

The `train_model.py` script includes:

- Loading the preprocessed data
- Training multiple models (e.g., Logistic Regression, Random Forest, etc.)
- Evaluating model performance using cross-validation
- Saving the trained model for future use

## Model Predictions

The `predict_model.py` script includes:

- Loading the trained model
- Making predictions on the test dataset
- Saving the predictions to a CSV file for submission to Kaggle


Feel free to customize this README to better fit your project!
