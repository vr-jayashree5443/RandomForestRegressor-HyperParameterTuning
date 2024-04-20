# RandomForestRegressor-HyperParameterTuning

## Overview
This project aims to enhance the predictive accuracy of a RandomForestRegressor model for predicting the selling price of used cars. Initially, a RandomForestRegressor model is employed, which yielded an accuracy of approximately 89%. The subsequent section focuses on optimizing the model's performance through hyperparameter tuning.

## Contents
- **Random Forest**: Initial exploration and implementation of RandomForestRegressor.
- **EDA, DE, DM, DC, DV**: Exploratory Data Analysis (EDA) including Data Exploration (DE), Data Manipulation (DM), Data Cleaning (DC), and Data Visualization (DV).
- **Feature Selection**: Identification of significant features using ExtraTreesRegressor for subsequent model training.
- **Split Data**: Segmentation of the dataset into training and testing sets.
- **Model Selection**: Selection of RandomForestRegressor for predictive modeling.
- **Hyperparameter Tuning**: Optimization of model performance through hyperparameter tuning using RandomizedSearchCV.
- **Training**: Training of the RandomForestRegressor model with the tuned hyperparameters.
- **Prediction**: Utilization of the trained model to predict selling prices for test data.
- **Performance Evaluation**: Evaluation of model performance using metrics such as R-squared score.

## Usage
To utilize this project:
1. Clone the repository.
2. Ensure all necessary dependencies are installed (e.g., pandas, numpy, sklearn).
3. Run the `RandomForestRegressor HyperParameterTuning.ipynb` notebook.

## Dataset
The dataset utilized in this project can be accessed via the following link: [Car Dekho Dataset](https://raw.githubusercontent.com/sahilrahmann/Price_prediction_of_used_Cars_-Predictive_Analysis-/master/cardekho_data.csv).
