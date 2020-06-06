# Hackerearth--Novartis-Competition

In this competition hosted on Hackerearth website Novartis is challenging us to predict if the server will be hacked or not.
We are given data with columns :
  1. Incident Id : Unique identifier of the incident log
  2. Date : Date of incident occurence
  3. X_1 - X_15 : 15 anonymized columns having logging parameters
  4. Multiple_offense : Target column : 1 for a hack and 0 for no
  
We are given almost 24000 rows of data and 18 columns for model training, you can see the EDA and the model building process in the code in which I used random forest classifier, lightgbm classifier and XGboost classifier to classify the target values as 0 or 1.
The data given to us is highly imbalanced in terms of target variable hence I used SMOTE technique for sampling to deal with the bias or imbalance in the given data
