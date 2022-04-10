# bikesharing
Analyzing and visualizing bikesharing data from Citibike using Tableau.

[link to dashboard](https://public.tableau.com/app/profile/mugunthan.rengarajah/viz/CitibikeAnalysis_16488389133580/Story1?publish=yes)

## Overview of Analysis
The purpose of the analysis is to inspect data provided by Citibike, a bikesharing organization to analyze and determine patterns and relationships between users of different genders. The dataset captures bikesharing data from August of 2019.

## Results
The subsequent paragraphs will explain each individual visualization in the Tableau story.

### Visualization 1: Number of Rides
![image_name](https://github.com/Mugunthan24/bikesharing/blob/main/images/number_of_rides.png)
The visualization above shows the total number of rides Citibike has provided to its users. The total includes all users of the service in August of 2019 regardless of customer type and gender.

### Visualization 2: Checkout Times for Users
![image_name](https://github.com/Mugunthan24/bikesharing/blob/main/images/checkout_time_for_users.png)
The Checkout Time for Users chart shows the relationship between the minutes a bike is rented out for and the number of bikes rented during that time.

### Visualization 3: Checkout Times per Gender
![image_name](https://github.com/Mugunthan24/bikesharing/blob/main/images/checkout_times_per_gender.png)
The Checkout Time per Gender chart shows the relationship between the minutes a bike is rented out for and the number of bikes rented during that time. Each line in the graph represents one of three gender groups:  - Male
- Female
- Unknown Gender

### Visualization 4: Gender Breakdown Table
![image_name](https://github.com/Mugunthan24/bikesharing/blob/main/images/gender_breakdown.png)
The Gender Breakdown Table provides a breakdown of the number of rides provided by Citibike per gender type.

### Visualization 5: Gender Breakdown Pie Chart
![image_name](https://github.com/Mugunthan24/bikesharing/blob/main/images/gender_breakdown_pie_chart.png)
The Gender Breakdown Pie Chart provides a chart of the Gender Breakdown table to make the differences in the number of rides per gender more apparent.

### Visualization 6: Trips by Weekday per Hour
![image_name](https://github.com/Mugunthan24/bikesharing/blob/main/images/trips_by_weekday_per_hour.png)
The chart is a heat map that shows when the service is most fequently used at each hour of the day per weekday. The darker a section is, the more frequently the bikesharing service was used during that day and time.

### Visualization 7: Trips by Gender (Weekday per Hour)
![image_name](https://github.com/Mugunthan24/bikesharing/blob/main/images/trips_by_gender_weekday_per_hour.png)
Similiar to the chart above, the heat map shows when the service is most fequently used at each hour of the day per weekday per gender. The darker a section is, the more frequently the bikesharing service was used during that day and time.

### Visualization 8: User Trips by Gender by Weekday
![image_name](https://github.com/Mugunthan24/bikesharing/blob/main/images/user_trips_by_gender_per_weekday.png)
The heat map above shows the frequency that each gender uses the Citibike service each day of the week. Along with a breakdown for each day of the week, there is a breakdown for each user type (Customer, and Subscriber).

## Summary
The subsequent paragraphs below will summarize the findings from the analysis and provide suggestions for additional visualizations that can be used for future analysis.

### Summary of Results
The following conclusions can be gathered from the Citibike data from August of 2019:
- More males than females use the Citibike service
- Users of the Citibike service usually use the service for 5 minutes.
- There is greater use of the Citibike service during the morning and evening rush hours amongst both males and females
- Proportionally, males and females roughly use the service the same amount at each hour and day of the week
- Most users of the service are subscribed
- Most of the unsubscribed users have not disclosed their gender

### Suggestions for Additional Visualizations
Suggestions for additional visualizations are:
- A clustered column bar chart where the x-axis is categories of various birth year ranges and the y-axis is the number of people using the service for each user type
- A table that contains the number of subscribed and unsubscribed users of the service between different birth year ranges
- A map that shows points of the start location for users of the service for each gender. The point for the start location will be larger the more often users start their trip at that location (a similiar visualization can be created using end locations)
- A map that shows points of the start location for users of the service for each user type. The point for the start location will be larger the more often users start their trip at that location (a similiar visualization can be created using end locations)
- A heat map that shows how frequently the service is used at different hours of the day each day of the week for each user type