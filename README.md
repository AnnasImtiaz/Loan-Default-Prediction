# Loan-Default-Prediction

The initial code file first tries to understand data and it's features.

After performing EDA and univariate / bivariate analysis of the data, correlation analysis was performed. Additionally, VIF was used to determine multicollinearity. Although some features did show high VIF factors, since the number of features is already limited, none of the features were dropped.

Next, it was determined that the dataset is imbalanced. Therefore, the alogorithms were run using both the default parameters as well as weights = balanced.

The algorithms that were run were Decision Tree, Random Forest, KNeighbours, Logistic Regression. All these models were run using both default parameters as well as weights = balanced parameter. Finally, ADA Boost and XGBoost boosting methods were run. Evaluation metrics used on the models were Accuracy, Precision, Recall, F1 Score and ROC_AUC_Score.

The top three models were used for Cross validation
