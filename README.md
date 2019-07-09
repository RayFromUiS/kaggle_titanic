# Project description
This is a try on Kaggle titanic competion,based on learning from Udacity course, Intro to ML

1. Load and preprocess the image dataset
2. Train the classifier on your dataset
3. Use the trained classifier to predict on test data

# Project flow
* Load and preprocess from [here]https://www.kaggle.com/c/titanic/
  * Inspect data correlation with surivived rate
  * Split data into two subsets
* Initiate the traing process
  * Bulid training function
  * Have different classfier compared
  * Optimize the hyperparameters
* Predict dataset
  * Using best classifier to predict

# Implementation
**import relevant libraries**
1. Data loading and Preprocessing
  * Plot columns of 'Pclass','Title','Gender','SibSp' with survived column
  * One hot enconding on such category columns
2. Trainging initiating
  * Using Naieve Bayes,Adaboost,RandomForest classifer as comparision classifers
3. Grid search on highest accuracy algorithm
  * set estimators,learning as gird search paramters
  
# Software and libraries
1. Python 3.7
2. NumPy
3. pandas
4. Sklearn
5. matplotlib
6. seaborn



