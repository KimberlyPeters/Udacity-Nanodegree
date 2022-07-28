# Ford GoBike System Data
## by Kimberly Peters

## Dataset

> We will investigate Ford GoBike System Dataset, assess its quality and tidiness, then clean it which called data wrangling.

> Ford GoBike System Dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

> The dataset originally consists of 183,412 rows and 16 columns and Most variables are numeric and concerns three major things as follows:

- Trip (duration_sec, start_time, end_time)
- Station (start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude)
- User (bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip)

> After assessment and cleaning, new columns were created to help in analyzing and exploring the data. The updated dataset consists of 19 columns now and the new columns are:

- Trip (duration, start_hour, start_day, start_month)
- User (member_age)

## Summary of Findings

- Most users are subscribers and Dominant gender is Male  
- Average duration of trips is about 10 mins.
- The lowest number of trips are in the weekend (Saturday and Sunday) while the top number of the trips is on Thursday.
- The rush hours of number of trips are 7 (7 am)and 18 (6 pm) while the number of the trips is the least and decreasing rapidly after midnight until dawn.
- Subcribers have done more number of rides than Customers
- Subscribers tends to rent bikes for shorter duration while Customers tends to rent bikes for longer duration

## Key Insights for Presentation

> User Type, trip duration and their weekday usage:

- Most users are subscribers
- Average duration of trips is about 10 mins.
- Subcribers have done more number of rides than Customers
- Subscribers tends to rent bikes for shorter duration while Customers tends to rent bikes for longer duration

> Gender, trip duration and their weekday usage: 

- Male riders counts are three times more than the Female riders. Other gender count is lesser when compared to male and female genders
- Average trip duration is highest for "Other" gender category
- Trip duration is slightly higher for females than males.
- 'Other' gender has the most average trip duration especially on Sundays



```python

```
