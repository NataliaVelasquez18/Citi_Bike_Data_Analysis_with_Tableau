# CitiBike Venture Analysis

The purpose of this analysis is to gain insights from the CitiBike business in order to have an understanding of whether or not it is an attractive business to invest.

---

## Overview of Approach

Using Tableau we analyzed one month data from the CitiBike operation in the city of New York.  The month analyzed is August due to the good weather conditions.
Some external data from research such as price of rides and cost of mainteinance of bikes was included in the analysis.

The dataset contains 2,343,746 rows that correspond to rides.  One of the columns of the dataset, tripduration, was converted to Datetime data type using Python.  We can see the result of the conversion in the following image:

<img src="https://github.com/NataliaVelasquez18/Citi_Bike_Data_Analysis_with_Tableau/blob/main/Resources/converting_trip_duration_to_datetime.png" width = "700" height= "250"/>

---

## Analysis


### Revenue

* There are two types of users: occassional customers and subscribers.  Customers represent the 19% and Subscribers represent the 81% from the total rides.  
* The vast majority of rides in both groups were in between 0-30 minutes. 
* A small portion of the revenue was calculated for customers.  We multiplied the number of 0-30-minute rides for customers times $3.5, which is the price published on the CitiBike's website.
* It is necessary to get more data to understand how many unique subscribers rode in August and be able to calculate the accrued revenue for those using the monthly subscription price.


<img src="https://github.com/NataliaVelasquez18/Citi_Bike_Data_Analysis_with_Tableau/blob/main/Resources/Revenue.png" width = "700" height= "500" />


### Costs of maintainance

* As we can see, the majority of the rides occurred in Manhathan.  Also, the vast majority of rides were short, in between 0-30 minutes.
* There are a total of 13,983 bikes that were used in the month of August.
* The cost of mainteinance of a bike goes from $58 to $140.  We calculating the cost using $120 as an estimate for mainteinance per bike.
* We recommend obtaining more data that help us understand how ofter are bikes taken for maintainance.  Some bikes might not be used very much and might not require maintainance as ofter as others.


<img src="https://github.com/NataliaVelasquez18/Citi_Bike_Data_Analysis_with_Tableau/blob/main/Resources/Cost_of_maintainance.png" width = "700" height= "500" />

### Demographics 

* Female represent 28% and male 72% of total rides
* When we analyze customers vs subscribers by gender, we can see that the two genders follow the same pattern.
* The vast majority of rides showed riders between 25 and 30 years old.

img

### Bike usage by weekday, gender, and hour




<img src="https://github.com/NataliaVelasquez18/Citi_Bike_Data_Analysis_with_Tableau/blob/main/Resources/Daysofweekbyusertypeandgender.png" width = "700" height= "500" />

<img src="https://github.com/NataliaVelasquez18/Citi_Bike_Data_Analysis_with_Tableau/blob/main/Resources/daysofweekbygenderandhour.png" width = "700" height= "500" />


