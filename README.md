# Meta-Learning-for-Autonomous-Machine-Learning-Project
This project implements an AutoML system using AutoKeras to automatically select the best models and hyperparameters for predicting wine quality. The dataset used is the Wine Quality Dataset from the UCI Machine Learning Repository.
Project Overview
The aim of this project is to use AutoKeras, an open-source AutoML tool, to build a model that predicts wine quality based on various chemical properties. AutoKeras simplifies the process of model selection and hyperparameter tuning by automating these steps and searching for the best-performing models.

Main Tasks:

Implement AutoKeras to handle the Wine Quality dataset.
Automatically search for the best model using AutoKeras.
Evaluate and save the best model for future use.

Features
Fixed acidity
Volatile acidity
Citric acid
Residual sugar
Chlorides
Free sulfur dioxide
Total sulfur dioxide
Density
pH
Sulphates
Alcohol
Target Variable
Quality: Wine quality score (0-10)
AutoML Framework
This project uses AutoKeras for AutoML:

AutoKeras automatically searches for the best model architecture and hyperparameters through max_trials (configurable number of model variations).
The dataset is split into training and testing sets (80/20 split), and the model is evaluated based on test accuracy.
