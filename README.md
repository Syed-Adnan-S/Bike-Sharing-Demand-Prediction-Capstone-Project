# Bike Sharing Demand Prediction Capstone Project

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Project tile - Seoul Bike Sharing Demand Prediction

### <b>Description:</b> 
This is a supervised ML (regression) capstone project on bike sharing demand prediction given by [Alma Better](https://www.almabetter.com/).

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### <b>Problem statement:</b>
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

![pic1](https://user-images.githubusercontent.com/85065799/200127764-29477a72-21b9-4bc8-97cd-6bb650395442.jpg)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

#### <b>Note:</b> Dataset is provided by the company, Alma Better.

### <b>Dataset description:</b> 
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Attribute Information:
* Date : year-month-day
* Rented Bike count - Count of bikes rented at each hour
* Hour - Hour of he day
* Temperature-Temperature in Celsius
* Humidity - %
* Windspeed - m/s
* Visibility - 10m
* Dew point temperature - Celsius
* Solar radiation - MJ/m2
* Rainfall - mm
* Snowfall - cm
* Seasons - Winter, Spring, Summer, Autumn
* Holiday - Holiday/No holiday
* Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### <b>Project Flowchart:</b>
1. Initial preparations(Loading the dependencies and the data)

2. EDA 

3. Clean-Up
     * Handling null values
     * Handling duplicate values
     * Removing Outliers

4. Feature engineering
     * Feature encoding
     * Checking correlation for feature removal
     * Removing Multicollinearity
     * Obtaining correlation between dependent and independent variables
     
5. Pre processing of the data
     * Target feature conditioning
     * Creating train and test dataset
     * Feature Scaling
    
6. Model implementation 
     * Linear Regression
     * Ridge Regression
     * Lasso Regression
     * Random forest regression

7. Model explainability

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### <b>Conclusion:</b>

1. EDA insights:

  * Most number of bikes are rented in the Summer season and the lowest in the winter season.
  * Over 96% of the bikes are rented on days that are considered as No Holiday.
  * Most number of bikes are rented in the temperature range of 15 degrees to 30 degrees.
  * Most number of bikes are rented when there is no snowfall or rainfall.
  * Majority of the bikes are rented for a humidity percentage range of 30 to 70.
  * The highest number of bike rentals have been done in the 18th hour, i.e 6pm, and lowest in the 4th hour, i.e 4am.
  * Most of the bike rentals have been made when there is high visibility.

2. Results from ML models:

  * Random Forest Regression is the best performing model with an r2 score of 0.6645.
  * Lasso Regression(L1 regularization) is the worst performing model with an r2 score of 0.4264.
  * Actual vs Prediction visualisation is done for all the 4 models.
  * All 4 models have been explained with the help of SHAP library.
  * Temperature and Hour are the two most important factors according to all the models.

3. Challenges faced:

  * Removing Outliers.
  * Encoding the categorical columns.
  * Removing Multicollinearity from the dataset.
  * Choosing Model explainability technique.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<b> For further information you can check the google colab file added in the repository. 

If you find any mistakes or have any suggestions for me, please reach out to me, all the criticism is heartly welcomed.

You can also reach out to me for project collaborations.

My Email Id - <u>syedshabbir107@gmail.com</u>

My LinkedIn profile - [Profile](https://www.linkedin.com/in/syed-adnan-s-2b899b228/)</b>

### Thankyou for tagging along to the end.
