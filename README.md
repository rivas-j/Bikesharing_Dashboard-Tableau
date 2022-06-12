# Citi Bike Sharing Challenge


You must use the five visualizations that you created in Deliverable 2.
You must use at least two visualizations that you created in this module.
In your README markdown file, include the following:
## Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis is to study Citi Bike Usage data in New York with the goal of implementing a pilot bike sharing program in Des Moines, Iowa. Our goal is to build a sales deck for prospective investors using the power of tableau visualizations, with the help of Pandas to process the raw data.

Please see our Tableau Dashboard in the link below:

[Link to Dashboard](https://public.tableau.com/views/CitiBikeChallenge_16549181178130/CheckoutTimesforUsers?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link)

## Results: 

### Using the visualizations we have in our Tableau Story, here are the results of our analysis of NY Citi Bike Ridership data.

#### Checkout Times for Users

According to the below line graph, the vast majority of bike rides tend to last around 5 minutes:
![Checkout Times for Users](https://github.com/rivas-j/bikesharing/blob/2f0c073d7a3af81605c7ce4e20d065daf13d4f57/Images/1_Checkout_Times_for_Users.png)
#### Gender Breakdown

The below pie chart indicates that males are the major target demographic:

![Gender Breakdown](https://github.com/rivas-j/bikesharing/blob/2f0c073d7a3af81605c7ce4e20d065daf13d4f57/Images/2_Gender_Breakdown.png)

#### Checkout Times by Gender

Adding the gender layer on top of the trip duration data, we see that mostly males are using the citi bikes for short 5 minute rides:
![Checkout Times by Gender](https://github.com/rivas-j/bikesharing/blob/2f0c073d7a3af81605c7ce4e20d065daf13d4f57/Images/3_Checkout_Times_by_Gender.png)

#### Weekday Trips Per Hour

The below chart outlines peak ridership by weekday and hour. 8-9 AM and 5-7 PM tend to be peak ridership times on weekdays. Off peak times during the week tend to happen from 10 AM - 5 PM; however during the weekend we're seeing increased ridership during these same hours.

![Weekday Trips Per Hour](https://github.com/rivas-j/bikesharing/blob/main/Images/4_Weekday_Trips_Per_Hour.png)

#### Trips by Gender (Per Weekday Per Hour)

Adding the gender layer to Weekday Trips per Hour, we see that males account for the majority of ridership during peak hours.

![Trips by Gender (Per Weekday Per Hour)](https://github.com/rivas-j/bikesharing/blob/2f0c073d7a3af81605c7ce4e20d065daf13d4f57/Images/5_Trips_by_Gender_Weekday_per_HR.png)

#### User Trips by Gender by Weekday

The below chart indicates that the bulk of ridership tend to be subscribers:

![User Trips by Gender by Weekday](https://github.com/rivas-j/bikesharing/blob/2f0c073d7a3af81605c7ce4e20d065daf13d4f57/Images/6_User_Trips_By_Gender_by_Weekday.png)


#### Bike Repairs

Given the major potential costs associated with mechanical breakdowns, we've introduced this visual that tracks the bike IDs and how many repairs they've had:

![Bike Repairs](https://github.com/rivas-j/bikesharing/blob/2f0c073d7a3af81605c7ce4e20d065daf13d4f57/Images/7_Bike_Repairs.png)


## Summary

We've been able to process a CSV file with 2.3 Million rows of rider data and provide these helpful visual summaries for our sales pitch to investors. The above charts provide crucial information for our Iowa pilot. The data indicates that:

- Males are the target demographic
- Most riders are program subscribers 
- Peak ridership hours happen during morning and evening weekday commutes

Along with the above visualizations, here are two additional ideas to punch up our sales deck and set you up for funding success:
- Additional demographic data would be very helpful, we'd like to determine the age range of the majority of bike share users
- In order to determine proper liability coverage, we'd like to visualize the most common accident types for NY Citi Bike riders


