# NYC Bikesharing Report

## Overview
In this project I created a story on Tableau Public that reports specifically on the trip data.  Within the story are multiple visualizations, comparing types of users by gender, durations of bike trips by gender, and the most popular times to checkout a bike, to name a few.  To create the visualizations I used line graphs, heatmaps, bar graphs and a map of New York's five boroughs to plot which one contained the most bike sharers.

## Results

[NYC Citibike Analysis](https://public.tableau.com/app/profile/max.vincent/viz/NYCCitibikeAnalysis_16433114462670/NYCBikeSharing?publish=yes)


![Usertype vs. Gender](https://github.com/MaxV6ft4/bikesharing/blob/main/Images/Usertype_vs_Gender.png)

The first visualization is a heatmap that plots the amount of bikes used per day based on gender, for each type of bike user (customer or subscriber).  It is very clear that male subscribers are responsible for the lion's share of bikes used in August.

![Trip duration](https://github.com/MaxV6ft4/bikesharing/blob/main/Images/Tripduration.png)

The second visualization is a line graph that plots the number of bikes used based on trip duration.  About 146,000 bikes were used for 5 minutes, by far the most popular duration.  These were most likely comprised of people running errands in and around their neighborhood.

![Trip duration vs. Gender](https://github.com/MaxV6ft4/bikesharing/blob/main/Images/Trip_duration_vs_Gender.png)

The third visualization uses the same line graph as the second one, but splits it into three graphs based on gender (male, female and unknown).  The most popular trip duration was 5 minutes for both males and females, however many more males rode for this amount of time than their female counterparts.

![Premium Rush](https://github.com/MaxV6ft4/bikesharing/blob/main/Images/Weekday_vs_Hour.png)

The fourth visualization is a heatmap that plots the number of bikes used for each hour of the day versus the day of the week.  Both morning and evening rush hour contains the highest demand for bike sharing, but evening rush hour (especially on Thursdays) is just a little more popular than morning rush hour.

![Rush Hour Genders](https://github.com/MaxV6ft4/bikesharing/blob/main/Images/Weekday_vs_Hour_by_Gender.png)

The fifth visualization uses the same heatmap as the fourth one but is split into three heatmaps based on gender.  It is clear that male riders are primarily responsible for rush hour demand.

![August Peak Hours](https://github.com/MaxV6ft4/bikesharing/blob/main/Images/August_Peak_Hours.png)

The penultimate visualization is a bar graph that plots the total number of bikes used during each hour of the day for the month of August.  More than 200,000 bikes were used each hour during the evening rush!

![Manhattan](https://github.com/MaxV6ft4/bikesharing/blob/main/Images/Manhattan.png)

The final visualization is a map of New York City that contains a circle for each starting location of a bike used in the sharing program.  A great majority of them were used in Manhattan.

## Summary
New York City is much larger than Des Moines.  It will take plenty of convincing the local residents that a bike-sharing program is worth the investment.  However, the Tableau story I have created has, I believe, provided excellent reasons to go ahead with the program in Des Moines.  We have seen that the majority of users only rode the bikes for a period of 5 minutes.  This means they rode simply to run errands or get groceries in their neighborhood.  While the amount of time spent on the bike might be slightly longer in Des Moines to perform the same activities, the concept still holds strong.  Furthermore, the majority of bikes were used during morning and evening rush hours.  This factor will not change, as every US city deals with increased traffic during rush hour.  Finally, the majority of users in NYC were based in Manhattan.  Des Moines does not have multiple boroughs like New York, but as long as users stay within the city limits, the program should be a success.

### Further Exploration
If you wanted to visualize the tripduration data in greater detail, you could create a line or bar graph comparing trip duration based on birth year (and gender on top of that as an option).  Most likely the results would show the longer the trip, the younger the individual.  Additionally, a second map could be created to comapre the most popular start and stop stations based on gender to see where in Manhattan the most males and females ride.
