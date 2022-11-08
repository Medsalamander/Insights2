# Ford GoBike System Data
## by Victor Obi


## Dataset

> The dataset explores data obtained from the Ford GoBike system data. It contains 183412 rows and 16 columns and shed light on the bikeshare habits of users around greater San Francisco Bay area between feb 2019 and and march 2019. The dataset presented with some data quality issues such as - 
Start_time and end_time are listed as object datatype
duration_sec is measured in seconds
user_type, member_gender, bike_share_for_all_trip are listed as object datatype
bike_id, start_station_id and end_station_id are listed float and int datatype
Age column is missing
The above issues were resolved resulting in a dataset fit for exploration.

## Summary of Findings

> Preliminary analysis showed 2 unique user types- subscribers and customers. User age shows most users are between 18 to less than 38 years with 30-38 forming the largest age bracket. 74.5% of users are male compared to 23.4% of users. A plot of trip duration showed that most trips stayed under 52 mins. Bike share habits showed that only 9.8% of all users indicated that they used bike share for all trips compared to 90.2% who said no. Hourly trips is highest at 5pm, 8am and 6pm. Day of the month trip is highest on the 28th, 20th and 21st. Thursdays account for the highest day of the week trips followed by Tuesday and Wednesday. Age and Trip duration showed unusual points that required transformation.

> A substantial portion of all subscribers are male. Also, a large portion of all customers are males. Male subscribers account for over 70% of all trips.Female users logged in more trip time compared to male users. Customers account for more than 60% of all trip duration compared to subscribers.Trip duration is highest at 2am. 

> Customers of all genders logged in more trip time compared to subscribers of all genders. About 50% of all subscribers use bike share for all trips while the other 50% do not.Finally, 100% of customers admitted to not using bike share for all trips.

## Key Insights for Presentation


> Trip count is highest on thursdays with tuesdays and wednesdays in close second and third respectively. In otherwords, more users are keen to use the bike share services on the aforementioned days. Making more bikes available and ensuring they are properly charged on these days may encourage user satisfaction and by extension revenue.

> A breakdown of hourly trip duration shows a sharp peak in trip duration after midnight. In otherwords users log in more trip time between 2am and 4am. This is followed by a sharp drop which remains relatively stable till 10pm.

> A plot of trip duration by user type and gender shows that customers of all gender logged in more trip time when compared to subscribers of all gender. Female customers logged in more trip time compared to male customers. This is interesting because 74.5% of users are male compared to 23.4% of females.