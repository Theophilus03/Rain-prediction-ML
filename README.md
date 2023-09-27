# Rain-prediction-ML
![unnamed](https://github.com/Theophilus03/Rain-prediction-ML/assets/114735443/1e84ee4f-6cb5-4719-9cf4-bef459f1a74d)
A mahine learning project to predict whether it will rain tomorrow or not by using the Rainfall in Australia dataset. Those models will be evaluated using f1-score and AUC.

## Workflow
# Data Collection
[Rainfall Prediction in Australia dataset](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package) from Kaggle

# Data Preprocessing
1. Handling missing data (drop column with > 38% missing value and fill NaNs with column medians for the other)
2. Handling outlier with IQR method
3. Feature Engineering (label encoding and mapping wind direction labels to degrees)
4. Imbalanced Dataset was handled using SMOTE

# Model
we trained 3 model which is Random Forest, Logistic Regression, Gaussian NB  to find the best one. 

## Result
![download](https://github.com/Theophilus03/Rain-prediction-ML/assets/114735443/1905baf2-3172-4124-8494-1792c337ff9c)
The best model is random forest that obtained of 77% f1-score and have the largest AUC.
