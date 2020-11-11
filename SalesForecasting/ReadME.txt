
I took up this project as my ML Specialisation from IIT Roorkee.
This is an independent project.The data is from UCI Machine Learning Repository.However I downloaded the data from cloudxlab.

For completing this project I referred the following websites--

https://www.mariofilho.com/how-to-predict-multiple-time-series-with-scikit-learn-with-sales-forecasting-example/
https://machinelearningmastery.com/basic-feature-engineering-time-series-data-python/?unapproved=565831&moderation-hash=ebef39093b877934382116e66788d141#comment-565831

Instructions I received from cloudxlab--------

Forecast sales quantities of each store and each product.

Input data available:

Historical sales values 

Store ID

Product ID

Datetime

Sales value (dependent)

Historical Disposable Personal Income values 

Datetime

Disposable Personal Income value

Additional features that can be computed are:

Disposable Personal Income: As a leading indicator, this index changes before sales change. Observe the best lag that is of interest.

Modeling parameters, including test.length, seasonality, observation.freq, and timeformat, needs to be input as well.

Datetime

Date features: year, month, week of month, etc.

Time features

Season features

Weekday-and-weekend features

Holiday features: New Year, U.S. Labor Day, U.S. Thanksgiving, Cyber Monday, Christmas, etc.

Suggestions:

Consider only sales values greater than 20

Divide the dataset into 2 years of training set and last 1 year of test set.

Take a log transformation of the sales value (dependent variable)

Data source Acknowledgement: This dataset is taken from the UCI machine learning repository Azure-Blog-Storage-Template Data, and disposable income is taken from https://fred.stlouisfed.org/
