# Kaggle Competition: Prediction of Obesity Risk
The goal of this competition is to use various factors to predict obesity risk in individuals, which is related to cardiovascular disease. My approach is divided into two steps: 

1. Perform exploratory data analysis (eda) to understand the data (and its distributions) and relationship with the dependent variable. Along the way, we can uncover patterns and find meaningful insights that help guide us when creating the predictive model.

2. Build, tune, and assess performance on classification model of choice. Catboost was chosen due to its simplicity in handling categorical data without the need to encode beforehand.

(Final accuracy score on Kaggle: .90426) 

# Data
The train and test datasets were downloaded from Kaggle. They can be found in the Data folder.

# Prerequisites 
- The exploratory analysis is located in Code/EDA.ipynb. To run, install Jupyter Notebook. 
- The Catboost model is located in Code/KaggleModels.ipynb. To run, install Jupyter Notebook and then use pip install on the requirements in requirements.txt in the Code folder. 

