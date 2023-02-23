##Supervised Machine Learning Objectives
---
<ul>
  <li>Explain how machine learning algorithms are used in data analytics.</li>
  <li>Create training and testing sets from a specified dataset.</li>
  <li>Implement linear and logistic regressions by using scikit-learn.</li>
  <li>Create confusion matrixes for classification outputs.</li>
   <li>Calculate and apply fundamental classification algorithms: logistic regression, support vector machine (SVM), and k-nearest neighbors (KNN).</li>
  <li>Quantify and evaluate classification models by using confusion matrixes.</li>
  <li>Implement one-hot encoding in Pandas, and scaling and normalization with scikit-learn.</li>
   <li>Calculate and apply bagging and boosting methods to create and use ensemble algorithms.</li>
  <li>Describe regularization parameters for regressions, and select appropriate parameters for a given problem.</li>
  <li>Use Random Forests and LASSO regressions to assist in the feature selection process.</li>
  
</ul>

##Predicting Credit Risk
---
In this assignment, you will be building a machine learning model that attempts to predict whether a loan will be approved or not.

####Background
---
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. This data will be used to

You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.

####Instructions
---
####Retrieve the data
The data is located in the Resources folder.

lending_data.csv
Import the data using Pandas.

####Consider the models
---
You will be creating and comparing two models on this data: a logistic regression, and a random forests classifier. Before you create, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct! Write down (in markdown cells in your Jupyter Notebook or in a separate document) your prediction, and provide justification for your educated guess.

####Fit a LogisticRegression model and RandomForestClassifier model
---
Create a LogisticRegression model, fit it to the data, and print the model's score. Do the same for a RandomForestClassifier. You may choose any starting hyperparameters you like. Which model performed better? How does that compare to your prediction? Write down your results and thoughts.
