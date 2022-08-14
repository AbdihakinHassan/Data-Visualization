# Fordgobike Data Exploration

## by Hassan Abdihakin


## Dataset

> the fordgobike dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. contains 183412 rows 16 columns. among the columns are duration_sec,start_time,start_station_latitude,bike_share_for_all_trip,member_gender and age. for furher understanding on the data the link is here https://www.google.com/url?q=https%3A%2F%2Fvideo.udacity-data.com%2Ftopher%2F2020%2FOctober%2F5f91cf38_201902-fordgobike-tripdata%2F201902-fordgobike-tripdata.csv&sa=D&source=docs

## Summary of Findings

>my main features of study were age,duration_mintes, user_type and member_gender.i first studied on each of them to understand their nature of distrubution. most of them were right skewed with stretched outliers which i later dropped. when started  comparing against each other i found that age  aginst user type. subscribers are the had oldest trip makers on average around 38 by specific group named others.the longest duration trips from cutomers group were made by females and this could be due to their nature of care or maybe females do ride in distance. however the question on why females ride lenth was longer than any other gender needs to be further investigated.
## Key Insights for Presentation

> i focused on how gender types contribute to the overall trips made in a week. i also further went to study the user types's user type and their total trips per week. before visualizing i first grouped the data into gender type and visualized ech group in a bar graph. males made most of trips per week, followed by females and other made the least trips. i studied deep on their user type. after visaulizing with counter plot i found that females contribute less on customers but females subs are close to 40k. others are largely subsccribers while male are the highest controbuters of the overal subscribers and the highest on customers. this can be said that men are the trip makers of the company and bring the highest revenue