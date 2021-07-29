# Bikeshare

## Overview

Citi Bike is a bike share program in New York City (NYC) designed to provide a quick, affordable way to get around the city. Users are given the option to purchase annual membership or a short-term pass.  Users are allowed unlimited number of rides as long as a pass or membership is active.

This analysis will utilize data from the Citi Bike program in NYC, New York to see if it is worthwhile to invest in a similar program in Des Moines, Iowa.  The data from this study is extracted from public files released through [Citi Bike NYC](https://www.citibikenyc.com/system-data) and is focused on data from August 2019. 

Data visualizations can be viewed via [Tableau Public for Noelle Garza](https://public.tableau.com/app/profile/noelle.garza/viz/NYCCitibikeStory_16274229283040/NYCCitibikeAnalysis)

## Results

The Citi Bike program in NYC provides bike docking locations throughout all five boroughs (The Bronx, Brooklyn, Manhattan, Queens, and Staten Island) however, the Top Starting Locations are centralized around downtown Manhattan which may indicate it is popular with tourists as that area is most popular with out-of-towners.  Another explanation is that it is common for NYC locals who live in Manhattan to not have access to personal vehicles and parking is an issue so the Citi Bike program is a stress-free and affordable way to get around town.

We select and highlight eight of the most popular starting locations in different locations around the Top Starting Locations map to focus and identify common characteristics.  These popular locations had several characteristics in common, those are:
	* Located near some of the most popular subway stations (Penn Station, Grand Central, Union Square)
	* Located around parks such as Central Park, the Hudson River Greenway which not only offers views but a dedicated bike path closed off from car traffic, and the High Line, an elevated linear park over a mile long with dedicated trails free from car traffic.
	* Located near the piers (Lincoln Tunnel, Chelsea) which may be due to the availability of nearby sights but also may be popular access points to cross the Hudson river.

Next, we look at the most popular length for trip durations.  Based on the Trip Duration plot, the average bike trip duration is less than 30 minutes in length.  Under ideal conditions, a healthy person can bike about 5 miles in 30 minutes indicating that the bike program is primarily being utilized for destinations that are less than five miles apart.  The most popular trip duration is only 5 minutes in length which also suggests that the typical customer is utilizing the bikes as a mode of transportation or recreation rather than for exercise.

Another method for determining the motivations of the target consumer is to look at the daily and weekly usage habits.  A heatmap of the hourly stoptimes (that is, when a bike is returned after usage) for each day of the week shows that the most heavy usage occurs Monday – Friday between 7-9am and 5-7pm, which are timeframes also known as work week “rush hour”.  In other words, the average Citi Bike consumer utilizes the service during popular commuting times.  The heatmap also shows the next tier of consumer is the weekend user where popular Stoptimes increase around 10am to 7pm, that is during daylight hours.

Taking a closer look at the typical consumer, the data shows males tend to use the bike share service at higher numbers than females.  A pie chart demonstrates that males are using the service at more than twice the number of females.  While the count of males using the service is certainly higher, it is interesting to note that females do follow similar usage patterns as the males.  For example, in a plot of Checkout Times by Gender, males clearly show a higher bike count but both males and females show an average usage around 30 minutes with a peak usage around 5 minutes as demonstrated in the earlier plot for overall Checkout Times for all Users.

Looking at the heatmap of hourly stoptimes broken down by gender, the “Gender Stoptime” does indicate that females follow a similar trend to males where peak usage occurs during work week rush hour and during daylight hours on the weekend.  However, while patterns between male and female usage are consistent, the heatmap clearly indicates substantially more usage by males during those peak usage times.  One observation that may require a closer analysis is that Thursday rush hours tend to show the highest activity while rush hours on Wednesdays tend to be less active than the rest of the week.  It is recommended to look closer at what is happening on Wednesdays and Thursdays that drive this activity.

Finally, the User trips are broken down by gender, day of the week, and Usertype (single-use customer or subscriber).  The User Trips by Gender heatmap illustrates how the Bike-share program is most popular with males, and subscriptions are more popular than single use-use customers.  This is one of the most telling elements as users who take annual subscriptions are most likely to be local, regular users.  This is perhaps one of the most effective visualizations in this analysis which demonstrates that the primary consumer for a bike share program in NYC is a male who lives and/or works in the city and utilizes a subscription to bike around the city as a mode of transportation and/or recreation.


## Summary

Des Moines, the capital city of Iowa, features several parks including sculpture parks, botanical gardens, and a robust shopping scene including a lively Downtown Farmers' Market.  Des Moines does have an active cycling community and features more than 600 miles of connected walking, biking, and running trails where downtown is the culminating point for many area trails.  However, unlike NYC, parking options are readily available and reasonable priced.  Also, unlike NYC, most Iowans own vehicles and are able to get around town without heavy traffic.

Based on this analysis, it would appear the demand for a bike share program in downtown Des Moines may be lower than for a place like downtown Manhattan where access to cars are less common and other modes of transportation are in high demand.  However, there may still be a market for a bike-share program.  For a successful program, it would be advised to start with a smaller fleet than Citi Bike NYC.  It is recommended to look further into determining the proportionate number of bikes respective to the city population to anticipate demand in the downtown Des Moines area.  

Similar to the Citi Bike NYC program, it is recommended to place docking stations near popular hiking/biking trails, riverwalks, train or ferry stations, and any unique places where heavy foot traffic is anticipated.  Keeping in mind that average users will travel less than 5 miles, place the majority of docking stations within a 5-mile radius, ideally with stations located every mile along popular destinations.

Because the NYC bikeshare program was most popular during daylight and working hours, it is recommended to perform updates and maintenance activity on the bikes in the least active hours such as before 7am or after 8pm.   Based on the observation that Thursday rush hours tend to show the highest activity while rush hours on Wednesdays tend to be less active than the rest of the week, it is recommended to check what local activities may be different on Wednesdays and Thursdays in NYC.  For example, gather subway and bus activity data and map out whether there are similar patterns in other popular modes of public transportation.

