# Solar-Prediction-With-ML
Use weather and sky image data to make solar prediction with RNN, ANN, and linear model
Solar Power is a fluctuating energy. This variability can do harm to the grid with existing electricity. If we can predict the immediate power, not only can solar power plant utilize battery beforehand to balance the fluctuation of Solar power, but also the utility management system (like ​Taipower Company​) can correctly schedule spinning reserves and demand response. 
 
There are currently different time span of prediction, intra hour, intra day, and day ahead, in which the forecast skill decrease when time span decrease.Thus, our group aims to maximize the accuracy of prediction of intra hour and we select forecasting horizons of 1 min, 5 min, 15 min, 60min.  
 
In intra hour forecast, there are two dominant input mainly use in current thesis: 
1. Sky Images
2. Meteorological records: 
 a. ghi/dni solar irradiance
 b. solar elevation
 c. weather data The most popular model used is ANN and there are few literature use RNN to compare over ANN. Thus, our team design experiments to achieve two goals, one is to analyze the performance of RNN and pick Linear model and ANN as our comparison models. sky image and Meteorological input to predict solar irradiance. Then,we will do some comparison and discussion on which model performs better in terms of accuracy. 
