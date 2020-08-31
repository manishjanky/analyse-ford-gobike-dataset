# Usage trends of Ford Go Bikes
## by Manish Kumar


## Dataset

> The dataset contains Bay wheels trip data for 2017, from June till December. The same was sourced from this location (https://s3.amazonaws.com/fordgobike-data/index.html). The data contains details about the start and end location, start and end time etc. Below are all the details available for each trip.

* Trip Duration (seconds)
* Start Time and Date
* End Time and Date
* Start Station ID
* Start Station Name
* Start Station Latitude
* Start Station Longitude
* End Station ID
* End Station Name
* End Station Latitude
* End Station Longitude
* Bike ID
* User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)

Using the above details certain derived fields were created for ex. Day of the week, Time of the day (Morning/Afternoon/Evening), distance covered in the ride based on the start and end station.

## Summary of Findings

##### Before performing this analysis an assumption was made i.e. the distance between the start station and end station is the covered distance of the ride. And hence the distance between the given corrdiantes was calculated in kms.

The dataset had very limited information to be used. For example there was details only when the ride was taken and what was the pickup and drop location with the duration of the ride. The analysis would have been more effective if there would have been more details included such as total distance covered, age of the user, gender of the user etc. Those things would have made the analysis more interesting. 
Based on the available information below are the observation we have with the above mentioned assumptions.

* Most of the rides are by the Subscribers.
* Majority of the rides were taken on weekdays excluding weekends.
* Majority if the rides were short duration rides.
* Majority of the rides were not long in terms of the distance.


## Key Insights for Presentation

* The rides used are more during the weekdays while there is a huge drop in the number of ride over the weekends.
* Subscribers tend to take more rides as compared to casual users. The difference between both is hugge. Subscribers account for 79% of the total rides taken when only 21% were taken by casual users.
* Majority of the rides were for shorter duration (below 30000 seconds), which clearly indicate the use of rides for short distances.
