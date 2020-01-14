# Wind_speed_NY
Examples of code being used in New York wind speed predictions. More notebooks are being used with different methods. Inside of this repository is some of the examples and methods tested.  

“wind_eda_top_feat.ipynb” is code for exploratory data analysis. Also, top five features for each random forest model were selected then tested on the test data. This was done to see what are the top features for reach model when using random forest. 

“test_samples.ipynb” is code for testing different samples of the majority class in a classification. This was done to see how a random forest model did with different levels of sampling on the majority class. 

“Sampled_data_models” is a folder that has results from sampling the data by wind speed in three different levels less than 15 knots, between 15 and 30, and greater than 30. This was done to see if results were better when trained with this equal sampling. Also, a regression model was used to predict wind speed than classified if it was greater than 30. This was done because we are looking to see how a model did predicting rare events, which is over 30. Machine learning models used are linear regression, random forest, and XGBoost.

“Regression Model” is a folder that has results from test done using linear regression, random forest, and XGBoost. Same as “Sampled_data_models” folder, a regression prediction of wind speed was classified to see how well it did at predicting rare events. The second part of the notebooks are testing the results when a model is given different training data amounts. 

“Classification” is a folder that has results from classification of wind speed greater than 30 knots. Random Forest and XGBoost were used.  Test were done with and without a sample of the majority class.

