## Human Activity Recognition Project

A machine Learning model that predicts human activities such as standing, sitting, laying, walking upstairs, walking downstairs, etc from the Accelerometer and Gyroscope readings
of their smartphones. (Multiclass classification problem)

Various Machine Learning algorithms were tested and their hyperparameters were tuned to give the best accuracy.

Best accuracy was given by Logistic Regression and RBF SVM classifier (96.27%), followed by LinearSVC (95.55%). Tree based models gave less accurate results.


## STEP 1 : Exploratory Data Analysis

 Prepared training and testing dataframes from features given in text files. A total of 561 features are there.

-> Performed data cleaning.

-> Checked for data imbalance.

-> Found features that separate stationary and moving activities using different plots like distplot and boxplot.

-> Applied t-SNE on the data.


## STEP 2 : Machine learning Models

-> Trained various ML models:

      1. Logistic Regression
      2. Linear SVC
      3. Kernel SVM
      4. Decision Tree
      5. Random Forest Classifier
      6. Gradient Boosted decision Trees
      
-> Used Grid Search for all above models to find the best values for hyperparameters.

-> Used Cross Validation to get final accuracies for models using hyperparameter values found out by Grid Search.

-> Printed classification report, accuracy obtained and times taken for training and testing the models. Also plotted confusion matrix.

-> Pickle files of saved models are available in the models folder.

