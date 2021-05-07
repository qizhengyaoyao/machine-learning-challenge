# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

## Feature Selection

* Feature selection process is done by file Model/feature_selection.ipynb
* ExtraTreesClassifier/feature_importance function is used to check the importance of different variables.
* 20 variables are selected.

## Tune Models Parameters

* 5 models are trained and tuned: kNN, SVM, Logistic Regression, Random Forest and Deep Learning.
* Gridsearch is used to find the best parameters for the above models.

## Results and Analysis

The feature selection is tested. Models trained by the selected 20 variables have similar performance with the all 40 variables. This proves that we have filtered the insignificant factors.

All the tuned models have good performance (accuracy greater than 85%).

* Model 1 KNN model: Training Data Score = 0.8819 / Testing Data Score = 0.8839
* Model 2 SVM model: Training Data Score = 0.8735 / Testing Data Score = 0.8913
* Model 3 Logistic Regression model: Training Data Score = 0.8726 / Testing Data Score = 0.8919
* Model 4 Random Forest model: Training Data Score = 1.0 / Testing Data Score = 0.8839
* Model 5 Deep Learning model: Training Data Score = 0.9005 / Testing Data Score = 0.9005

In conclusion, all the above models can be used. Among these models, the deep learning model has the best perfromance.

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
