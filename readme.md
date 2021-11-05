# Ford GoBike System
## by Mustafa Ahmed


## Dataset

Ford GoBike is a bike-sharing system that allows people to use bikes as a transportation mean through different stations in San Francisco Bay Area. Data has 183412 observation regarding different features such as (Duration_min, start_station_name, end_station_name, user_type, member_gender) 

Before starting exploration, I've made some adjustments such as: Dropping unnecessary columns and null values , add column for age and Change duration to minutes. That lead to decrease number of columns to 10 and observations to 174952. 



## Summary of Findings

First I have started with univariate plots with main focus on number of trips/users against other features. I found that most of the trips takes between 10 to 13 minutes, majority of users are male, large porportion of our users aged between 25 and 35 years, most of the trips are made by subscribers, and trips are less in weekend than weekdays.

For bivariate plots, I focused on duration. There is a slight difference in trip duration against different features such as(gender, and user type). But age is negatively correlated with duration.

For multivariate plots, I Found that there is no effect for gender on trips through the weekdays or trips duration. But gender has an effect on user type, as there is a huge gap between male (the majority of users) and female users, For customers, we don't see that gap.    


## Key Insights for Presentation

For presentation, I started with duration based on age and gender, which indicated that there is almost no effect for gender on the relation between duration and users age. Then, I paid attention to how duration and number of trips are correlated taking into account(Gender, Weekday, and User Type). I found that number of users differ based on those three variables. When we look at duration, ther is a slight effect. 