# Bikesharing Dashboard with Tableau

<div align="center">
    <img src=images/citibike.webp>
</div>

## <div align="center">Utilize Tableau to Visualize Citi Bike Ridership Trends</div>

<p align="center">
<a href="#goals">Goals</a> &nbsp;&bull;&nbsp;
<a href="#dataset">Dataset</a> &nbsp;&bull;&nbsp;
<a href="#tools-used">Tools Used</a> &nbsp;&bull;&nbsp;
<a href="#results">Results</a> &nbsp;&bull;&nbsp;
<a href="#summary">Summary</a>
</p>

# <div align="center">Goals</div>

What should be true after this project is implemented? The objective is to demonstrate the project's value. Edit for clarity and remove any language specific to curriculum (i.e. fictional names, narratives). Make the report seem like a case study, not an assignment. Include a high-level overview of the analysis so that recruiters with limited technical knowledge can understand what your project is about without drilling down.  The key is to make everything easy for employers so they can review more of your work.

Sample: Puppy Analysis answers the question, how many puppies were adopted from shelters across the United States during the 2020 Covid-19 pandemic. Observes a total number of dogs adopted, breed demographics, and the number of dogs adopted by a state.”

Please see our Tableau Dashboard in the link below:

[Link to Dashboard](https://public.tableau.com/views/CitiBikeChallenge_16549181178130/CheckoutTimesforUsers?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link)

# <div align="center">Dataset</div>

I retrieved monthly ridership data from [Citibikenyc](https://www.citibikenyc.com/system-data) in CSV format, which will be my Tableau data source

- [Citi Bike Monthly Rider Data - August 2019:](data/201908-citibike-tripdata_new.7z) CSV file containing 2,344,223 rows of rider data

# <div align="center">Tools Used</div>
- **Tableau Desktop:** Powerful and robust data visualization software

# <div align="center">Results</div>

## Using the visualizations we have in our Tableau Story, here are the results of our analysis of NY Citi Bike Ridership data.

### Checkout Times for Users

According to the below line graph, the vast majority of bike rides tend to last around 5 minutes:
![Checkout Times for Users](images/1_Checkout_Times_for_Users.png)

### Gender Breakdown

The below pie chart indicates that males are the major target demographic:

![Gender Breakdown](images/2_Gender_Breakdown.png)

### Checkout Times by Gender

Adding the gender layer on top of the trip duration data, we see that mostly males are using the citi bikes for short 5 minute rides:
![Checkout Times by Gender](images/3_Checkout_Times_by_Gender.png)

### Weekday Trips Per Hour

The below chart outlines peak ridership by weekday and hour. 8-9 AM and 5-7 PM tend to be peak ridership times on weekdays. Off peak times during the week tend to happen from 10 AM - 5 PM; however during the weekend we're seeing increased ridership during these same hours.

![Weekday Trips Per Hour](images/4_Weekday_Trips_Per_Hour.png)

### Trips by Gender (Per Weekday Per Hour)

Adding the gender layer to Weekday Trips per Hour, we see that males account for the majority of ridership during peak hours.

![Trips by Gender (Per Weekday Per Hour)](images/5_Trips_by_Gender_Weekday_per_HR.png)

### User Trips by Gender by Weekday

The below chart indicates that the bulk of ridership tend to be subscribers:

![User Trips by Gender by Weekday](images/6_User_Trips_By_Gender_by_Weekday.png)


### Bike Repairs

Given the major potential costs associated with mechanical breakdowns, we've introduced this visual that tracks the bike IDs and how many repairs they've had:

![Bike Repairs](images/7_Bike_Repairs.png)

# <div align="center">Summary</div>

We've been able to process a CSV file with 2.3 Million rows of rider data and provide these helpful visual summaries for our sales pitch to investors. The above charts provide crucial information for our Iowa pilot. The data indicates that:

- Males are the target demographic
- Most riders are program subscribers 
- Peak ridership hours happen during morning and evening weekday commutes

Along with the above visualizations, here are two additional ideas to punch up our sales deck and set you up for funding success:
- Additional demographic data would be very helpful, we'd like to determine the age range of the majority of bike share users
- In order to determine proper liability coverage, we'd like to visualize the most common accident types for NY Citi Bike riders

[Back to top](#project-name)
