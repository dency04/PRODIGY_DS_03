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
Accuracy: 0.8892935178441369
Classification Report:
               precision    recall  f1-score   support

           0       0.94      0.94      0.94     10968
           1       0.51      0.51      0.51      1389

    accuracy                           0.89     12357
   macro avg       0.72      0.73      0.72     12357
weighted avg       0.89      0.89      0.89     12357

## Dataset
https://archive.ics.uci.edu/ml/datasets/Bank+Marketing
