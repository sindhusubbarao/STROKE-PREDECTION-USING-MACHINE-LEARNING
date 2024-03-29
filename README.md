# STROKE-PREDECTION-USING-MACHINE-LEARNING
Stroke is a severe cerebrovascular disease with potentially fatal consequences. Early prediction of stroke risk can significantly aid in preventive measures and timely medical interventions. In this project, we aim to develop a robust machine learning model to predict the likelihood of stroke based on various demographic, lifestyle, and clinical factors.
The dataset comprises 5110 patient records with attributes such as age, gender, hypertension, heart disease status, average glucose level, body mass index (BMI), smoking status, work type, residency type, and stroke event occurrence. The target variable is whether a patient has experienced a stroke or not.

APPROACH:-

Data Preprocessing: Handle missing values, perform feature engineering, and encode categorical variables.
Exploratory Data Analysis (EDA): Understand the distribution of variables, investigate correlations, and identify significant predictors.
Model Selection and Hyperparameter Tuning: Experiment with various machine learning algorithms such as logistic regression, random forest, and gradient boosting. Tune hyperparameters to optimize model performance.
Model Evaluation: Assess models using appropriate evaluation metrics such as accuracy, precision, recall, F1-score, and area under the ROC curve (AUC).
Interpretation and Validation: Interpret model results, validate against test data, and ensure generalizability.

CONCLUSION:-

After extensive hyperparameter tuning and experimentation, the Random Forest model emerged as the best-performing classifier for predicting stroke risk in the dataset. The model achieved an accuracy of 0.8838878016960209 on the test set, demonstrating its effectiveness in distinguishing between individuals at high and low risk of experiencing a stroke.
