This repository contains notebooks for preparing data, comparing machine learning packages, and training models. The goal of this project is to preprocess data, evaluate different machine learning algorithms, and train a predictive model.

Repository Structure
Comparison_Of_Packages.ipynb: Notebook comparing different machine learning packages and initial test on data.
Preparing_Data_For_Training.ipynb: Notebook for data preprocessing and preparation of dataframe for training the models.
Training.ipynb: Notebook for training and evaluating machine learning models from sklearn(lr,rf,xgboost,mlp) and pytorch(mlp).

1. Comparison of Packages
This notebook (Comparison_Of_Packages.ipynb) compares different machine learning packages and evaluates their performance on a given dataset.

Steps:
Load and preprocess the dataset.
Compare the performance of various machine learning models.
Visualize the results and select the best package.

2. Preparing Data for Training
The notebook (Preparing_Data_For_Training.ipynb) focuses on data preprocessing steps necessary for model training.

Steps:
Load the raw dataset.
Handle missing values, outliers.
Do Feature Selection
Save the processed data for model training.

3. Model Training
The notebook (Training.ipynb) covers the training, evaluation, and selection of the machine learning model.

Steps:
Load the preprocessed data.
Define and initialize the model.
Train the model using training data and validation.
Perform Student T-Test to choose best models from all trained models
Evaluate the model's performance of best model on testing data.
Save the trained model for future predictions.
