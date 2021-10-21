This project makes predictions on onset of diabetes using XGBoost model.

The Dataset used for this is called Pima-Indians-Diabetes Dataset by UCI Machine Learning.

This Jupyter notebook can also be used like an template to understand how to fit models to your dataset and to make easy predictions.





Below is the description for the dataset:

You can download the dataset from Kaggle: https://www.kaggle.com/uciml/pima-indians-diabetes-database

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.





Content of the dataset is as follows:

The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.




Intuition behind choosing XGBoost Model:

It is a decision-tree based ensemble machine learning model that uses a gradient boosting framework. The idea behind choosing XGBoost to make predictions was that Pima Diabetes dataset is a relatively small dataset with tabular implementation of data. Decision-tree algorithms are currently best in class to make predictions on structured datasets that are relatively small-to-medium. Also, it is a perfect combination of software and hardware optimization techniques that yield superior results using very less computing resources in a very short duration of time.
