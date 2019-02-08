# Forest-Cover-Prediction

This is a kaggle classification problem to predict the forest cover type depending on the input variables. There are 7 levels in the target column.
https://www.kaggle.com/c/forest-cover-type-prediction/

Models built: Random Forest, Random Forest with PCA, Extra trees classifier, XGBoost

Best accuracy is obtained with extra trees classifier model with feature engineering and grid search.

Random Forest with PCA - Accuracy on Test data - 69%

Random Forest with cross validation - Accuracy on Test data - 73.80%

Extra trees Classifier with feature engineering - Accuracy on Test data - 81.48%
mtry = 13
number of trees = 500
3 fold cross validation
Grid Search
