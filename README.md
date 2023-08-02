# Seoul-Bike-Sharing-Demand-Prediction-EDA-Regression-Classification-Unsupervised
Project Name - Seoul Bike Sharing Demand Prediction
Project Type - EDA/Regression/Classification/Unsupervised
Contribution - Individual
Name - Aasheerwad Sharma

Problem Statement -

Many urban cities are currently introducing rental bikes in order to improve mobility comfort. Obtaining the right bike count for stable supply of rental bikes is important to make the rental bike available and accessible to the public at the right time, thereby reducing waiting times. A stable supply of rental bikes becomes a major issue for the city as time goes on.

Describing dataset -

The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Dataset Information -

Date : year-month-day

Rented_Bike_Count - Count of bikes rented at each hour

Hour - Hour of he day

Temperature-Temperature in Celsius

Humidity - %

Windspeed - m/s

Visibility - 10m

Dew point temperature - Celsius

Solar radiation - MJ/m2

Rainfall - mm

Snowfall - cm

Seasons - Winter, Spring, Summer, Autumn

Holiday - Holiday/No holiday

Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

EDA Conclusion: 

As we can see that summer has the highest number of bikes rented, 37%. This could be because of the vacation mood created in summer and also the increase in the number of tourists. Winter however is the season where the least number of bikes are rented, 8%.
As we can see that the majority of the bikes rented are on days which are considered as No Holiday.
As we can see that the most number of bikes rented are in the temperature range of 15 degrees to 30 degrees.
We can see here that most of the bikes are rented when there is no snowfall at all. A similar result is seen for rainfall too, i.e the most number of bikes are rented when there is no rainfall.
As we can see that the majority of the bikes are rented for a humidity percentage range of 30 to 70
Here we can see that the highest number of bike rentals have been done in the 18th hour, i.e 6pm, and lowest in the 4th hour, i.e 4am.
Use of ranted bike count is more in 5th, 6th, and 07th Month

Basic Insights

In our analysis, we initially did EDA on all the features of our datset. We first analysed our dependent variable i.e, 'Rented Bike Count' and also transformed it. Next we analysed categorical variable and dropped the variable who had majority of one class. we also analysed numerical variable, check out the correlation, distribution and their relationship with the dependent variable. We also removed some numerical features who had mostly 0 values and hot encoded the categorical variables.

Next we implemented 7 machine learning algorithms Linear Regression, Lasso,Ridge,Support Vector Regression,Decision Tree, Random Forest, XGBoost and XGBoost with Grid Search CV. We did some hyperparameter tuning to improve our model performance.

Final Observations:

Out of all above models XGBRegressor gives the highest R2 score of .918

No overfitting is seen.

We can deploy XG Boost Gridsearch CV model.

