
# Diabetes-Prediction
##### Problem Statement
The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.

### Overview of Project

**D**iabetes **M**ellitus (DM), commonly referred to as diabetes, is a group of metabolic disorders in which there are high blood sugar levels over a prolonged period. Type 1 diabetes results from the pancreas's failure to produce enough insulin. Type 2 diabetes begins with insulin resistance, a condition in which cells fail to respond to insulin properly. As of 2015, an estimated 415 million people had diabetes worldwide, with type 2 diabetes making up about 90% of the cases. This represents 8.3% of the adult population. 

The [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database) can be used to train machine learning models to predict if a given patient has diabetes. This dataset contains measurements relating to Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age.

### About the Dataset
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

### Result and Conclusion
In this case study, we looked at predicting diabetes for 768 patients. There was a reasonable amount of class imbalance with just under 35% of patients having diabetes. There were no missing data, and initial looks at the data showed it would be difficult to separate patients with diabetes from those that did not have diabetes.

Three advanced modeling techniques were used to predict whether or not a patient has diabetes. The most successful of these techniques proved to be an **AdaBoost Classification technique**, which had the following metrics:

**Accuracy score for adaboost** : 0.7792207792207793

**Precision score adaboost** : 0.7560975609756098

**Recall score adaboost** : 0.5636363636363636

**F1 score adaboost** : 0.6458333333333333

Based on the initial look at the data, it is unsurprising that Glucose, BMI, and Age were important in understanding if a patient has diabetes. These were consistent with more sophisticated approaches. Interesting findings were that pregnancy looked to be correlated when initially looking at the data. However, this was likely due to its large correlation with age.
