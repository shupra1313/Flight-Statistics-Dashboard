Flight-Statistics-Dashboard
flight

TEAM MEMBERS:
Ananya Yetigadda
Gabriela Cantu
Shruthi Elkal
Shubha Prashanth
Tinku Supakar
Project Description:
The project demonstrates visualizations with multiple views on the same data, each of which is able to drill down into the data based further in each view. Our visualizations show different views on flight delay data across major, airports, airlines, routes and months of the year. The visualization story follows average arrival and departure delays and attempts to analyze the hidden causes of these delays. Using publicly available data from Bureau of Transportation Statistics (BTS), the overall goal of this project is to investigate the general basis of flight delays and identify airlines, airports and routes with the highest delay rates.

Datasets:
The original dataset pertaining to flight delays (2013-2018) was downloaded from the Bureau of Transportation Statistics (BTS) website BTS Dataset which stores, analyzes and maintains the transportation data. The data set analyzed contains information for 14 carriers and 316 airports. The data was downloaded as .csv file which made it easy to read into python using the csv module. During the exploratory data analysis, more than 100 variables, were examined for insights in this project. The variables we mainly considered were:

Numerical continuous variables: Year, Month, number of flights, Arrival delay, Departure Delay
Categorical variables: Airports, Carriers
Categorical variables with continuous values: Delay causes
Calculated continuous variables: Flight Delay (%), Avg Arrival delay, Avg Departure Delay
In addition, for the exact geo locations for each airport, we used the dataset from the following website: Geo locations Datasets

Research Questions:
How does flight delay percentage change over time in comparison to the number of arrived flights? Is there any variation in delay pattern during different quarters of the year?
How long are the flights delayed due to each cause? Does the proportion change over time?
Is there a correlation between delay percentage and the number of arrived fights?
Which carrier performs better?
Which kind of flight delay is increasing and decreasing over the years?
Research Findings:
Visualization 1 (Airport Traffic by geographic location) - This chart shows the busiest airports based on the flight traffic. We found that Atlanta, GA: Hartsfield-Jackson Atlanta International as the busiest airport with highest total number of flights and Owensboro, KY: Owensboro Daviess County Regional as the least busiest with lower flight traffic. Month by Month breakdown of the data with flights delayed less than 15 minutes shows atlanta as the busiest airport that being said it has less percentage of delayed flights and San Francisco has the highest percentage of delayed flights.
page1

Visualization 2 (Arrival and departure delay by Airport and Route) – Both the charts show the number of flights and the routes round the year. The charts show the origin and destination airports and routes, which have the average delays. Some carriers and routes are excluded from the data since the number of flights operated by those airlines or on those routes was so few that any delays would not have a significant impact on the total average. It highlights the average arrival and departure delay rates for each route from any origin and destination airport. This visualization paints a picture of how some of United State's most popular airlines and routes stack up against each other in scheduling. The purpose of this dashboard is to show the number of flights through airports does not always correlate to higher average delays.
page2 page3

Visualization 3 (Airports Vs Delays): The first chart shows the highest delays pertaining to the top 10 airports. Chicago O’Hare (ORD) shows the highest delays for late aircraft delay with the total of 12231 hrs for the years 2013-2018, followed by Hartsfield -Jackson Atlanta Airport (ATL) with 11175 hrs . (Carriers Vs Delays) : The second graph shows the highest delays caused by the carriers And the Oscar goes to SouthWest with 12470 hrs caused by weather, security, NAS, late aircraft, carrier delay with a close competitor being American Airlines. (Sankey Diagram): The curves with the most thickness shows the most delays, and as per the diagram we can see that the ORD airport has the most delays caused by late aircraft delay. And SouthWest with the most delays with late aircraft delay.
page4

Visualization 4 (Airlines Performance): The first chart rates the airlines based on average arrival delay time for different years (2013-2018). For example, for 2018 based on average arrival delay time, Allegiant Air was the best airlines while southwest airlines came out to be the worst. The second chart compares the airlines performance for top ten busiest airports in USA based on arrival delays. For instance, for Chicago O'Hare International airport if you don’t want to wait at the airport, fly with Virgin America Airlines.
page5

Future Scope:
Conduct full and rigorous statistical analysis to confirm the relationship between the observed pattern of seasonal changes and increase/decrease of delayed flights.
Use historical weather data around airports in Machine Learning algorithm to predict flight delays.
Analyze correlation between flight prices and delays.
Analyze flight safety: which airline is the safest?
