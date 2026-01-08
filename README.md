A machine learning model for prediction of cancer risk

This model can be used to predict cancer risk levels of patients - low, medium or high:
1. Data preparation - Keep patient data as same format as those in the excel file
2. Predict - best_model.preict(scalar.transform(new_data))
3. Decode - le_risk.inverse_transform(prediction)
