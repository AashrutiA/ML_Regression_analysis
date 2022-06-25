# <p align ="center"> Seoul Rental Bike Sharing Demand Prediction </p>

<p align ="center"> <img src="https://user-images.githubusercontent.com/101988419/175788349-52ad2013-ca3e-492d-9fdd-d20bbaef6593.png"     </p>



<p align ='justify'> Rental Bike are slowly getting its acclaim in the urban cities for better mobility comfort to the public. In order to maintain the smooth operation, availability and accessibility of the rental bike with lesser waiting time period is the most crucial concern. Thus, it is very necessary to understand the features driving the demand of rental bikes in order to fulfill the demand. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.</p>

## 1.Business Problem 
<p align ='justify'>Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes .

## 2. Approach

1.	Firstly, we will deep dive into the dataset after loading it to understand each of  the features. After carefully inspecting the features, we framed out hypothesis  for EDA such as most active hours, season, month, weekday for rented bike and many more to understand the patterns and relation between different variables.<br>
2.	Data Preprocessing & feature engineering of the dataset involving removing duplicates, identifying and handling missing values, outliers, dropping the irrelevant columns to make our dataset more reliable.
3.	Analyzing and Visualization of the dataset utilizing relevant plots and charts and infer the insights out of that.
4.	Model Building involving implementation of different regression machine learning algorithms like linear regression, tree based regression models to build the model followed by training the dataset and predict the test result.
5.	Comparison of all models based on r2 score and find the best performing model to predict the rental bike sharing demand.
  
 ## 3. Result
  
<p align ="center"> <img src = "https://user-images.githubusercontent.com/101988419/175788158-0b021620-2e4f-457d-9bbf-b6b20f78d445.png" </p>
  
  
## 4. Conclusion
 <p align ='justify'>Almost all algorithms performed really well on both training dataset and testing dataset so we can say that variance is less and no issues of overfitting are present. Both "Random forest regression" and "Gradient Boosting regression(GridSearch CV) has highest R2 score of 98.8% and 94% respectively. Performance on "Decision Tree" algorithm is comparatively less with an R2 score of 68%. </p>


