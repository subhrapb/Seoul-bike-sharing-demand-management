Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Data source: https://archive-beta.ics.uci.edu/dataset/560/seoul+bike+sharing+demand
Present work involves Visual explorations, data pre-processing and baseline models to predict bike demands each hour of the day based on weather & holiday patterns.

Accuracy score achieved accross following models 
  LinearRegression: R-squared score = 0.664
  Ridge: R-squared score = 0.664
  Lasso: R-squared score = 0.664
  ElasticNet: R-squared score = 0.614
  DecisionTreeRegressor: R-squared score = 0.750
  RandomForestRegressor: R-squared score = 0.861

Future work: Optimization of demand model to improve prediction accuracy using Principal component analysis technique to analyse effects.
