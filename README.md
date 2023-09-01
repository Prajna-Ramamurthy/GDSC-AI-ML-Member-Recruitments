# GDSC-AI-ML-Member-Recruitments
This Kaggle competition challenges participants to use a modified version of the POWER NASA Temperature Dataset to build forecasting models.

**Overview**

Welcome to the Googoda.com, the Travel Booking Company, where we aim to help you plan the perfect vacation. As a data scientist in our team, you are tasked with predicting the vacation rate for popular tourist destinations across the globe.

The vacation rate is an essential metric for us as it helps us determine which destinations to promote during specific times of the year. We believe that the vacation rate is dependent on various factors, such as temperature, humidity, and surface pressure.

To help our customers plan their dream vacations, we need to predict the vacation rate accurately. We have collected historical data from a popular tourist destination, and we need your expertise to create a predictive model that can forecast the vacation rate with high accuracy.

Your task is to analyze the provided dataset and use machine learning techniques to predict the vacation rate for the based on temperature, humidity, and surface pressure. You will need to preprocess the data, perform feature engineering, and select an appropriate machine learning algorithm to build a predictive model.

To test the accuracy of your model, we will provide a test dataset with unseen data. The model's performance will be evaluated based on the Root Mean Squared Error (RMSE) between the predicted and actual vacation rates.

We believe that your analysis and predictive model can help us provide more accurate and personalized vacation recommendations for our customers. So, get ready to pack your bags and explore the world of data science with us!

This Kaggle competition challenges participants to use the POWER NASA Temperature Dataset to develop accurate forecasting models. The dataset provides historical Weather readings from various locations around the world, and participants must build models that can predict future temperatures at these locations based on past readings.

**Data**

This dataset contains environmental data collected from NASA’s data access viewer. It consists of weekly meteorology and solar data collected from a city from January 1982 to December 2022.

The data is split into two groups:

Training set (train.csv)
Test set (test.csv)
The training set should be used to build your machine learning models. For the training set, we provide the values for each feature and the output variables (T2M, QV2M and VACATION_RATE). You are free to perform any kind of data preprocessing, feature selection, and apply relevant algorithms to train and improve your model’s performance.
The test set should be used to evaluate your model's performance on unseen data. For the test set, we do not provide the values for the target variables. It is your job to forecast these values.
However, you are required to submit only the forecasted values for VACATION_RATE.
Note:
Please note that the column ID is an encoding for week numbers. It starts at week 0 (encoded for the first week of January 1982) and continues.
The VACATION_RATE is a floating point value between 1 and 100. The sample submission shows VACATION_RATE as an integer just to act as an easy reference
In your submission.csv file you should have 2 columns ID (700 values from 1440 to 2139) and VACATION_RATE only. You can see this clearly in the sample_solution.csv

Files
train.csv - the training set
test.csv - the test set
sample_solution.csv - a sample submission file in the correct format

DATA DICTIONARY
Variable	        Definition	                                                Explanation
T2M	              Temperature at 2 Metres (°C)	                              Target Variable #1
QV2M	            Specific Humidity at 2 Meters (g/kg)	                      Target Variable #2
WS10M	            Wind Speed at 10 Meters (m/s)	
PS	              Surface Pressure (kPa)	
T2M_MAX	          Maximum temperature at 2 metres above ground level (°C)	
T2M_MIN	          Minimum temperature at 2 metres above ground level (°C)	
T2M_RANGE	        Temperature range at 2 metres above ground level (°C)	      This is the difference between the maximum and minimum temperatures over a given period of time
RH2M	            Relative Humidity at 2 Meters (%)	
VACATION_RATE	    VACATION_RATE	                                              Target Variable #3. It is affected by all the other features in the dataset
