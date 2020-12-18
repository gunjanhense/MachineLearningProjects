This data is available on kaggle-https://www.kaggle.com/c/mercedes-benz-greener-manufacturing.This is a high dimensional data.The target variable is time,we need to predict the time a car spends on test bench using the other variables.We cant use any intuition because the variables are unnamed.Most variables are binary categorical(0,1).

Both train and test sets are available on kaggle.But I chose just to work with the train set and divide it further into train,test as I wanted to use my model to make predictions.(The test set in kaggle does not have the target column).

I have started with random forest and ended concluded with XGBoost.Without gridsearch I have received an accuracy of 61%.


