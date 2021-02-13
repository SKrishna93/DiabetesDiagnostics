# DiabetesDiagnostics

## Objective:
To predict diabetes based on diagnostic measurements

## Description:
The objective is to predict whether a patient has diabetes or not based on certain diagnostic measurements.

## Details:
*	Dataset: National Institute of Diabetes and Digestive and Kidney Diseases – All female subjects
*	Diagnostic Features: BMI, insulin level, age, number of pregnancies.
* Preprocessing: Treating for missing values, removing outliers, feature selection by checking numerical features association using Pearson’s correlation, scaling the data.
*	Classifier – Gradient boosting Classifier with max_depth = 12, n_estimators = 64 and learning rate = 0.05 was attained using random search giving 90% average accuracy score for 5-fold cross-validation. 
*	Result – The model achieves 91% precision, 79% recall, an f1 score of 85% and 94% AUC
*	The above model was registered on Azure ML workspace and deployed using Azure Container Instances (ACI)
