# sdc486L
# repository for sdc486 lab

#Housing Price Prediction Project
This projects develops a machine learning pipeline to predict median house values using housing data from a 1990 california housing census with fetch_california_housing
This project includes:
Data Preprocessing and Scaling
Linear Regression modeling
Neural Network and Model Training
Model Evaluation
Model Comparison
Scenario Simulation Analysis

The primary goal is to evaluate how different modeling techniques perform and how housing value is affected

The dataset includes the following features
MedInc (Median Income)
HouseAge
AveRooms
AveBedrms
Population
AveOccup
Latitude
Longitude

Target variable is Median House Value
Features were scaled with StandardScalar

From the analysis: 
Median income and population are driving factors in home prices
Neural Networks amplify nonlinear interactions between features
Linear models provide interpretability while neural networks provide flexibility. 

Dependencies:
pandas
numpy
matplotlib
scikit-learn
tensorflow
openpyxl
xgboost
seaborn
