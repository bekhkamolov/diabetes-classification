# Diabetes-Classification
In this project I tried to predict whether the patient has diabets or not in two different way: using a simple interpretable model(DecisionTreeClassifier) and using black box model (RandomForestClassifier). This open source dataset consists of 8 attributes and one label column Outcome

At first I did some EDA (exploratory data analysis) to get familiar with columns, checking the missing values.

### Distinct Values per Column
Pregnancies:17 distinct values
Glucose:136 distinct values
BloodPressure:47 distinct values
SkinThickness:51 distinct values
Insulin:186 distinct values
BMI:248 distinct values
DiabetesPedigreeFunction:517 distinct values
Age:52 distinct values
Outcome:2 distinct values

# Baseline: 
Majority class (label = 0). Since the data is imbalanced (34.9% no diabetes), we can have a simple baseline that predicts all data points in the test set as the majority class, in this case is label 0 (no diabetes). With baseline our confusion matrix looks like this:

## Confusion Matrix

![Confusion Matrix](baseline_confusion_matrix.png)
