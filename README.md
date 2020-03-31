# EEL891 Machine Learning

This repository contains the final project for the 2018.2 subject *EEL891 Machine Learning* lectured for the Electronics and Computer Engineering course at the Federal University of Rio de Janeiro. 

The goal of the project is to create a solution for the the [Kaggle's Boston Housing Price competition](https://www.kaggle.com/c/boston-housing). 

## Boston Housing Price

This well-known competition provides a dataset containing features of houses in Boston and their respective prices. Using this dataset, competitors are encouraged to develop models that best predicts the price of new houses. 

The solution notebook `Previsão preço imóveis.ipynb` (written in brazilian portuguese) contains the report of the proposed solutions, which has the following sections: 

1. Library Imports 
2. Dataset Loading
3. Preprocessing 

    - Categorical Variables
    - Numerical non-binary Variables 
    - Numerical binary Variables

4. Model Training

    - Linear Regression
    - Lasso Regression
    - Passive Agressive Regression
    - Elastic Net
    - Kernel Ridge Regression
    - Gradient Boost 
    - LGBoost 
    - Bayesian Ridge 
    - Support Vector Regression
    - Random Forest Regressor
    - Ensemble of previous models using a Random Forest Regressor

5. Discussions

All models were evaluating using a 10-fold cross-validation and the average *Root Mean Squared Percentage Error*, as well as its standard deviation. 

The ensemble achieved a result of *0.130741 +/- 0.037786* for the validation sets. 