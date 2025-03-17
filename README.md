# Weather-forecast

This repository constitutes of Python project that performs Weather Forecasting based on the machine learning model and learning techniques. The project comprises of the use of several libraries such as Pandas to help with the data management and manipulation.

Step 1: The historical data is loaded into a dataframe

Step 2: The rows for the missing target variable are removed to avoid corruption of data and ensure that the model is built on real-time values with no truncating of data

Step 3: The target variable is selected, which in this case is the amount of rain (precipitation)

Step 4: the data is split into training and validation datasets

Step 5: The columns that are missing values by more than 20% are removed

Step 6: The columns with missing values are imputed by the simple imputation and one hot encoder method

Step 7: The data is pre-processed before going through the pipeline

Step 8: A machine learning regression method is selected, which in this case, RandomForestRegression is being used

Step 9: The data is passed through the pipeline

Step 10: The training data is pre-processed and fitted to the model

Step 11: The validation data is pre-processed and predictions calculation

Step 12: The model is evaluated for MAE (Mean absolute error)

Step 13: The test data is used to predict the weather for the new year

Step 14: An analysis is carried out and the data is plotted to validate the results and predictions
