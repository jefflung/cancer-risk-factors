A machine learning model for prediction of cancer risk
-------------------------------------------------------

After the comparison of all models, the best model is Logistic Regression and its turned accuracy is 0.8600

This model can be used to predict cancer risk levels of patients - low, medium or high:
1. Data preparation - Keep patient data as same format as those in the excel file
2. Predict - best_model.preict(scalar.transform(new_data))
3. Decode - le_risk.inverse_transform(prediction)
