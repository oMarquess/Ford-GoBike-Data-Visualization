# Ford Go-Bike Data Visualization
## by Salami Redeemer Okekale


## Dataset

> The Ford GoBike System is a bike rental program in the US. Within a service area, you can pick up and drop off a bicycle, based on your current needs. This project analyzes and visualizes the data collected from users of the GoBike program. The data can be found at https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv.

The dataset includes:

> an ID number for each bicycle
> how long it was rented for, in seconds
> the beginning and end staton ID, latitude, longitude and station name
> the start and end time
> the year the user was born
> the gender of the user
> whether the user has a subscription to the service or not​There are 2252058 rows and 15 columns.
There were some cleaning needed to the dataset, which were performed at the Data wrangling stage. This included:

> Deleting the rows without gender or birth year
> Only use ages that are reasonable. Check for abnormally old or young values and remove them
> Change data types, including times to datetimes, and
> Categorize user_type and member_gender
> Extract months and days of the week from start_time



## Summary of Findings

> Observation(1): Tuesdays and Thursdays are the most popular days for using the bike sharing system, however Mondays, Wednesdays and Fridays also see relatively high patronages, saturdays and sundays are not popular as the rest of days.
> Observation(2): The most patronage is often during the hours of 8 and 9 in the morning, and in the afternoon at the hours of 5-6pm.
> Observation(3): The mean age of a user is 35.5 years old.
> Observation(4): Most of the users of this system are male.
> Observation(5): Majority of the users of this system are Subscribers by User_type.
> Observation(6): The most popular station is Market St at 10th St, followed by San francisco caltrian station 2, with Market St at Dolores St. being the least.
> Observation(7): Customers have a relatively low usage of the bike share system with a small increase on the weekends whilst Subscribers are the    opposite.
> Observation(8): It was observed that all ages love to trip less than 200 minutes.
> Observation(9): Subscribers have a wider range of ages whilst Customers tends to have mostly younger users.
> Observation(10): Though not a huge difference, male riders tend to have shorter trips compared to female users, indicated by both a smaller median and  shorter Inter Quartile Range.
> Observation(11): Subscribers take trips mostly during 8-9 am and 4-6 pm which is usually working hours of a company.
> Observation(12): The customer type of users spend more time on trips compared to the subscriber type.
> Observation(13): It can be seen from the above plot that subscribers ride much shorter/quicker trips compared to customers on each day of the week.
> Observation(14): We can see clearly the trips taken by customers and subscribers on weekdays and weekends.



## Key Insights for Presentation

> For my presentation, I will focus on the difference in usage for customers and subscribers. On the later plots, I will show how gender also comes into play. I will first show the univariate results, such as usage on days of the week, and usage over months. I will then continue to see how adding more variables influences the results. My conclusion is that whether a user is a customer or a subscriber has the biggest influence on results, compared to gender.