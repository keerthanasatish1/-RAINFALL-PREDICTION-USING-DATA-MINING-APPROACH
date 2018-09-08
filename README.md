# -RAINFALL-PREDICTION-USING-DATA-MINING-APPROACH
PROPOSED SYSTEM
In this we predict the occurrence of rainfall in the city of Montreal. Prediction is a challenging task, for Rainfall it’s even more complex and dynamic. It depends on various parameters like maximum temperature, minimum temperature, Relative humidity, DewPoint, wind speed etc... Which are changing from time to time and weather Prediction varies with the geographical location along with its atmospheric variables
This project is implemented Using Matlab and it predicts the occurrence of rainfall based on the following steps:
Step 1 - We collected the weather forecast data of Montreal for the last 27 years and predict the rainfall for the next few months, using data mining approach. For this, we gathered the weather forecast data of the year 1990 to 2017 from Government of
Canada’s website.
Step 2 - Since data obtained is real time, Data pre-processing and data transformation is made on raw weather data set. The extracted raw data set has 9 attributes. Here, we are use attributes like maximum temperature, minimum temperature, average relative humidity, dew point, wind speed, wind gust, average pressure (sea) and average pressure (station) to predict the total Precipitation.
Step 3 - The dataset was cleaned and divided into two sets, a training set includes data from 1990 to 2015 and a test set with data of 2017.The model is trained using the training data and trained data will serve as database and the model is tested for accuracy based on test data.
Step 4 - For this purpose, we are using some of the Regression methods to predict the rainfall in the coming days. The Regression methods used here are:
• Regression tree model
• Bagged Decision Trees model
• Neural network
• GLM regression model
• Ensemble method
• Gaussian process regression (GPR)
Step 5 - After this we write the codes for different algorithms under regression method, we take test data and run the forecasting algorithms.
Step 6 – Then we compare the predicted result with the actual result. This is done by plotting graphs to compare the actual with the predicted result as well as the forecast error (Prediction error).
Step 7 – Finally, we use simple percentage error calculation to compare error and accuracy percentages of different regression methods.
