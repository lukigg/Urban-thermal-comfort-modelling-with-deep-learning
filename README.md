# Machine Learning Project: Data Preparation and Model Training

This repository contains notebooks for preparing data, comparing machine learning packages, and training models. The goal of this project is to preprocess data, evaluate different machine learning algorithms, and train a predictive model.

## Repository Structure

- `Comparison_Of_Packages.ipynb`: Notebook comparing different machine learning packages and initial test on data.
- `Preparing_Data_For_Training.ipynb`: Notebook for data preprocessing and preparation of dataframe for training the models.
- `Training.ipynb`: Notebook for training and evaluating machine learning models from sklearn (lr, rf, xgboost, mlp) and PyTorch (mlp).

## Notebooks

### 1. Comparison of Packages

This notebook (`Comparison_Of_Packages.ipynb`) compares different machine learning packages and evaluates their performance on a given dataset.

#### Steps:
1. Load and preprocess the dataset.
2. Compare the performance of various machine learning models.
3. Visualize the results and select the best package.

### 2. Preparing Data for Training

The notebook (`Preparing_Data_For_Training.ipynb`) focuses on data preprocessing steps necessary for model training.

#### Steps:
1. Load the raw dataset.
2. Handle missing values and outliers.
3. Do feature selection.
4. Save the processed data for model training.

### 3. Model Training

The notebook (`Training.ipynb`) covers the training, evaluation, and selection of the machine learning model.

#### Steps:
1. Load the preprocessed data.
2. Define and initialize the model.
3. Train the model using training data and validation.
4. Perform Student T-Test to choose the best models from all trained models.
5. Evaluate the performance of the best model on testing data.
6. Save the trained model for future predictions.
