# Communicate US Airlines Data Findings
## by Ahmed Hashish


## Dataset

The U.S. Department of Transportation's (DOT) [Bureau of Transportation Statistics](http://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp) (BTS) tracks the on-time performance of flights operated by large air carriers. Summary information on the number of on-time, delayed, canceled and diverted flights appears in DOT's monthly Air Travel Consumer Report, published about 30 days after the month's end, as well as in summary tables posted on this website. BTS began collecting details on the causes of flight delays in June 2003. Summary statistics and raw data are made available to the public at the time the Air Travel Consumer Report is released. There are 292,669 records in our dataset, each record contains monthly statistics for each airline with a certain destination airport.

There are 292,669 records in our dataset, each record contains monthly statistics for each airline at a certain airport. Our dataset variables are listed below:

| Variable Name | Description |
| :---------- | :---------- |
|'year'|Year|
|'month'| Month|
|'carrier'| Airline Code|
|'carrier_name'|Airline Name|
|'airport'|Airport Code|
|'airport_name'|Airport Name|
|'arr_flights'|Number of flights arrived at the airport|
|'arr_del15'|Number of flights delayed (>= 15minutes late)|
|'carrier_ct'|Number of flights delayed due to their airlines|
|'weather_ct'|Number of flights delayed due to weather|
|'nas_ct'|Number of flights delayed due to National Aviation System|
|'security_ct'|Number of flights delayed due to security|
|'late_aircraft_ct'|Number of flights delayed due to a previous flight using the same aircraft being late|
|'arr_cancelled'|Number of cancelled flights|
|'arr_diverted'|Number of diverted flights|
|'arr_delay'|Total time (minutes) of delayed flights|
|'carrier_delay'|Total time (minutes) of delayed flights due to their airlines|
|'weather_delay'|Total time (minutes) of delayed flights due to weather|
|'nas_delay'|Total time (minutes) of delayed flights due to National Aviation System|
|'security_delay'|Total time (minutes) of delayed flights due to security|
|'late_aircraft_delay'|Total time (minutes) of delayed flights due to a previous flight using the same aircraft being late|


## Summary of Findings
In the exploration, I found that there was a strong positive relationship between the total time of delayed flights and the time of delayed flights committed by carrier itself. Similarly, the busy aircraft delay time has a strong positive relationship with the total time of delayed flights. Additionally, I answered the following interesting questions:
1. What are the top 5 airports that are home to more delays or cancellations?
2. Which year has the worst flights delays?
3. Which year has the highest rate of cancelled flights?
4. What are the most/least efficient airlines? and what are the top 5 efficient airlines?
5. which cause variable is mostly affected the total delay time?
6. For permanent airlines only, which one has the best improvements year by year?
7. What are the preferred times for flights to occur?


## Key Insights for Presentation

For the presentation, I focus on the effects of delay causes on the total delay time. I start by introducing the two time variables - the total delay time and the delay time caused by carrier, followed by distribution for each of them on logarithmic scale, then plot the transformed scatterplot for the two variables.

Afterwards, I introduce some visualizations to answer some interested questions using violin plots, clustered bar chart, and line plot.
