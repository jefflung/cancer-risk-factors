A machine learning model for prediction of cancer risk
-------------------------------------------------------

<img width="1000" height="500" alt="2025-08-15_MLSS_Cover" src="https://github.com/user-attachments/assets/93a6dc27-648f-4f45-861a-509a0022342e" />

After the comparison of all models, the best model is Logistic Regression and its accuarcy is 0.906646 and 0.8600 after being tuned.

This model can be used to predict cancer risk levels of patients - low, medium or high:
1. Data preparation - Keep patient data as same format as those in the excel file
2. Predict - best_model.preict(scalar.transform(new_data))
3. Decode - le_risk.inverse_transform(prediction)
