# Abstract:
The goal of this project is to use classification models to predict miscarriage through several features. We worked with data related to pregnant women. Several classification models were applied to obtain the best model capable of predicting better, and at the end, the user enters several inputs to predict whether miscarriage will occur or not.

# Design:
There are many pregnant women who suddenly miscarry, which affects their psychological state, so we built a model that helps women predict whether or not they will continue to become pregnant through several inputs.

# Data:
The dataset consists of 15 features and 999926 observations:
(BMI,Nmisc,Location,Temp,BPM,Stress,BP,Biking,Walking,Driving,Sitting,Alcohol Consumption, Drunk)-> Inputs, and (Miscarriage/No Miscarriage) -> target variable.

# Algorithms:
* Models:Logistic Regression, Decision Tree,Random Forest,k-nearest neighbors (knn) ,xgboost, Support vector classifie (SVC), Gaussian Naïve Bayes (GaussianNB).
* Model Evaluation and Selection:Initially, the data was divided into 80 percent of the training data and 20 percent of the test data. Then the training data was divided into training data and validation data to compare several models and choose the best among them, then integrate the training data and validation data to train the model, and finally test the model using the test data that it has not been trained on.
* The model performance is measured using accuracy, f1, recall, precision, and the confusion matrix.
* Decision Tree is the best model.

# Tools:
Numpy and Pandas for Data Manipulation, Matplotlib and Seaborn for Data Visualization, (DecisionTreeClassifier,RandomForestClassifier,KNeighborsClassifier,xgboost,svm,GaussianNB)for model,(train_test_split)for model selection,(recall_score,accuracy_score,f1_score,precision_score,confusion_matrix)for evaluation,Program: Jupyter Notebook.

# Communication:
My project will be included on my GitHub page.
