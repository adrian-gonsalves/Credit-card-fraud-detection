# Credit-card-fraud-detection

Problem Statement

The problem statement is to predict fraudulent credit card transactions with the help of machine learning models.
In this project, we analyse customer-level data that has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group. 
The data set is taken from the [Kaggle website](https://www.kaggle.com/mlg-ulb/creditcardfraud) and has a total of 2,84,807 transactions; out of these, 492 are fraudulent.Since the data set is highly imbalanced, it needs to be handled before model building.

## Project pipeline
The project pipeline can be briefly summarised in the following four steps:

### Data Understanding: 
Here, we need to load the data and understand the features present in it. This would help you choose the features that you will need for your final model.

### Exploratory data analytics (EDA): 
Normally, in this step, we need to perform univariate and bivariate analyses of the data, followed by feature transformations, if necessary. For the current data set, because Gaussian variables are used, we do not need to perform Z-scaling. However, we can check whether there is any skewness in the data and try to mitigate it, as it might cause problems during the model building phase.

### Train/Test split: Now, we are familiar with the train/test split that you can perform to check the performance of your models with unseen data. Here, for validation, we can use the k-fold cross-validation method. We need to choose an appropriate k value so that the minority class is correctly represented in the test folds.

### Model building / hyperparameter tuning: This is the final step at which you can try different models and fine-tune their hyperparameters until you get the desired level of performance on the given data set. You should try and check if you get a better model by various sampling techniques.

### Model evaluation: Evaluate the models using appropriate evaluation metrics. Note that since the data is imbalanced, it is is more important to identify the fraudulent transactions accurately than the non-fraudulent ones. Choose an appropriate evaluation metric that reflects this business goal.
