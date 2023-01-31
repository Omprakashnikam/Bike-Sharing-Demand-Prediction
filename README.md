Problem Statement - The prediction of bike count required at each hour for the stable supply of rental bikes.

Conclusion - During the time of our analysis, we initially performed EDA on all of the features of dataset. We have analysed both numerical as well as categorical variables. For a good analysis we splitted the date column and added a new column as weekday_weekends. We also saw about the correlation and other relationships and found out that dew_point_temprature and temprature column are colinear and so we dropped the dew_point_temprature column. Also our output feature had some outliers value so we tried to fixed it by IQR method for indpendent variable and square rooting the values of output feature values.

Next we implemented 5 machine learning algorithms Linear Regression,lasso,elasticnet,decission tree and Random Forest We did hyperparameter tuning to improve our model performance. The results of our evaluation are:

Random forest Regressor gridsearchcv gives the highest R2 score of 99% for Train Set and 94% for Test set. We can deploy this model.
