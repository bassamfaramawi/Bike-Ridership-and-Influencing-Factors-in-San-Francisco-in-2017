# Ford GoBike Exploration¶

## by: Bassam Faramawi


## Dataset

This data is of bike ridership in San Francisco in the 2nd half of 2017. The data 
consisted of trip durations and attributes of approximately 519,700 bike trips, 
including The attributes included  `duration_sec`, `member_birth_year`, `member_gender`,
`user_type` and `start_time`&`end_time` features as well as additional measurements such 
as `bike_id`, `start_station_id`, and `end_station_id`. 
The dataset can be found in 
**[this link](https://www.lyft.com/bikes/bay-wheels/system-data)**.


## Summary of Findings

In the exploration, I found that there was a strong negative relationship between 
the trip duration and the member age, so that the youth customer prefer to take 
longer trip duration specially the ones between 31 yrs and 45 yrs by the reverse 
of older guys prefer to take shorter trip durations. The starting time of the trips 
has strong effect average number of trips in terms of hours of the day so the rush
hours witnessing a clear increase in activity of ridership, and in terms of weekdays
so the weekend has most acitivity than in workdays, and in terms of month so that
activity of ridership icreasing steady in summer season till it reaches the max in 
september and start to decrease in autumn season.
The month has effects on the ratio of the subscriber users to customer users so the 
percent of subscribers increase in summer till reaches september then start decreasing
in autumn seasons. In general, the subscriber activity is much more than the customers 
one.
The gender has great effect on the ridership, that there is a big space between the 
male and female bike rides.



## Key Insights for Presentation

For the presentation, I focus on just the influence of the five factors of trip.
I start by introducing the `duration_min` variable, followed by the `member_age`  distribution, followed by the difference between male and female ridership then in 
`member_gender` feature then plot the distributed DayHours.

Afterwards, I introduce each of the tow `user_type` & `hour` categorical variables 
in one plot to measure the activity using heat map plot. I then plot the relationship
between one numeric veriable `duration_min` andtow categorical veriables `month` and 
`weekday` by bar plot to decpit the change of activity.
The I decpit the strong negative relationship between the only two categorical 
veriables in the dataset using a scatter plot. 
The subscribers-customers ratio decpited by a stacked colored bar plot.

Finally, I used multivariate plots to deal with more than tow features in one plot, to
have the sufficient evidence of the previous measurements.
