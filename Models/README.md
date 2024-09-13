# Explanation of Contents

## File Name: Best RF Model
Best Hyperparameters: {'bootstrap': True, 'max_depth': 10, 'max_features': 'sqrt', 'min_samples_leaf': 4, 'min_samples_split': 10, 'n_estimators': 100}

<br>

## File Name: Best XGB Model
Best Hyperparameters: {'colsample_bytree': 1.0, 'gamma': 5, 'learning_rate': 0.01, 'max_depth': 3, 'n_estimators': 100, 'reg_alpha': 1, 'reg_lambda': 2, 'subsample': 0.6}

<br>

# Model Results

## Random Forest Results
* **Mean Absolute Error (MAE): 1.9467821317003164**
* **Root Mean Squared Error (RMSE): 2.372680695943936**
* **Training MAE: 1.8986799415670812**
* **Training RMSE: 2.259468144727309**
* **Cross-Validation MAE: 2.3795859173805205**

<br>

## XGBoost Results
* **Mean Absolute Error (MAE): 1.9968243885040287**
* **Root Mean Squared Error (RMSE): 2.5532722662428746**
* **Training MAE: 1.7757338047027589**
* **Training RMSE: 2.107246647250733**
* **Cross-Validation MAE: 2.343489589180265**

<br>

# Model Comparison Notes

## MAE & RMSE
Random Forest is performing better on the test set in terms of MAE and RMSE, suggesting it is better at generalizing to unseen data. <br> XGBoost has better training performance but might be slightly overfitting the data.

<br>

## Cross-Validation MAE
XGBoost has a marginally better Cross-Validation MAE, indicating that it has better performance across different splits of the data.

<br>

## Conclusion
Given that Random Forest has lower test error (MAE & RMSE), Random Forest is the better model in this case for generalization on unseen data. 
