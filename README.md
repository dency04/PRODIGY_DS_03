# PRODIGY_DS_03 - Bank Marketing Campaign: Decision Tree Classifier

## Task Description
In this task, I built a Decision Tree Classifier to predict whether a client will subscribe to a term deposit based on a dataset from a Portuguese bank's marketing campaign. The model was trained on labeled data and evaluated for classification performance using accuracy and detailed metrics.

## Technologies Used
- Python
- Pandas
- Scikit-learn (sklearn)

## Key Steps
- Loaded the Bank Marketing dataset 
- Applied label encoding to all categorical features
- Split the data into training and test sets
- Built a `DecisionTreeClassifier` model using scikit-learn
- Evaluated model performance using:
  - Accuracy Score
  - Classification Report (Precision, Recall, F1-Score)

## Output
Accuracy: 0.87 (example value)
Classification Report:
              precision    recall  f1-score   support
           0       0.90      0.95      0.93      1096
           1       0.67      0.47      0.55       174
