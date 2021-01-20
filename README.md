# Bikesharing-with-Tableau
# Bike sharing  data using Tableau

## Overview of the analysis: 
With the analysis of NYC bike sharing data and visualization we have to convince investors that a bike-sharing program in Des Moines is a solid business proposal. For this analyis we will create various visualizations on Tableau.Using Pandas we will convert the datatype of tripduration to datetime dataframe and convert the numeric values of gender to string values.These pre converted columns will speed up the visualizations rather than doing the conversions on Tableau and plotting the data.

## Results
### A. The below link is for the Tableau story that has visualizations created from the NYC bikesharing data 
[link to Tableau story](https://public.tableau.com/profile/akshaya1961#!/vizhome/Usertripsbygenderweekday2/Story-NYCBikesharingAnalysis)

### B. Below are the results of each visualization created in the Tableau story

#### 1. Checkout times for users:
![](https://github.com/Akshaya-Kamble/Bikesharing-with-Tableau/blob/main/Reference_Images/Checkout%20time%20for%20users.PNG)
This graph shows the length of time the bikes are checked out for all riders.The trip duration is shown in hours.
Looking at the graph we can conclude that most number of bikes were rented for the five hour trip duration.
[link to Tableau visualization](https://public.tableau.com/profile/akshaya1961#!/vizhome/Checkouttimeforusers_16105716359700/Checkouttimeforusers)


#### 2. Checkout times by gender:
![](https://github.com/Akshaya-Kamble/Bikesharing-with-Tableau/blob/main/Reference_Images/Checkout%20time%20by%20gender.PNG)
This graph shows the length of time the bikes are checked out for all genders.The trip duration is shown in hours.
Looking at the graph we can conclude that most number of bikes were rented by male riders for a selected trip duration than the female riders. We also have a number of riders whose gender is unknown and are marked in red.
[link to Tableau visualization](https://public.tableau.com/profile/akshaya1961#!/vizhome/Checkouttimesbygender/Checkouttimesbygender)


#### 3. Trips by weekday per hour:
![](https://github.com/Akshaya-Kamble/Bikesharing-with-Tableau/blob/main/Reference_Images/Trips%20by%20weekday%20per%20hour.PNG)
In this graph using heatmap we can conclude that more bikes are rented on a particular hour on a weekday. The dark colors are the hours with the highest number of bikes rented and the light colors show the least number of bikes rented. We can also see that most number of the bikes are rented on thursdays during 7am to 8am and 5pm to 7pm.
[link to Tableau visualization](https://public.tableau.com/profile/akshaya1961#!/vizhome/Tripsbyweekdayperhour/Tripsbyweekdayperhour)

#### 4. Trips by gender (weekday per hour):
![](https://github.com/Akshaya-Kamble/Bikesharing-with-Tableau/blob/main/Reference_Images/Trips%20by%20gender(weekday%20per%20hour).PNG)
In this graph we have the number of bike trips by gender for each hour of each day of the week as a heatmap. Since the male riders have rented more bikes the heatmap shows a lot of darker shades. We can also see a lot of bikes are rented during 7am to 8am and 5pm to 7pm for both genders as these hours have darker colors on the heatmap.
[link to Tableau visualization](https://public.tableau.com/profile/akshaya1961#!/vizhome/Tripsbygenderweekdayperhour/Tripsbygenderweekdayperhr)

#### 5. User trips by gender by weekday:
![](https://github.com/Akshaya-Kamble/Bikesharing-with-Tableau/blob/main/Reference_Images/user%20trips%20by%20gender%20by%20weekday.PNG)
This graph shows the number of bike trips by gender for each hour for each day of the week as a heatmap. Since the number of male riders are highest the heat map shows dark colors for this data. We can also see that we have more subscibers than customers.
[link to Tableau visualization](https://public.tableau.com/profile/akshaya1961#!/vizhome/Usertripsbygenderweekday/Usertripsbygenderbyweekday)

#### 6. August peak hours:
![](https://github.com/Akshaya-Kamble/Bikesharing-with-Tableau/blob/main/Reference_Images/August%20peak%20hours.PNG)
Since summer is a good time to visit New York there are probably more number of bike riders exploring the city. The graph shows how many bikes are rented on hour of the day in the month of August.With 5pm having the highest number of riders.
[link to Tableau visualization](https://public.tableau.com/profile/akshaya1961#!/vizhome/Usertripsbygenderweekday2/AugustPeakhours?publish=yes)

#### 7. Top starting locations:
![](https://github.com/Akshaya-Kamble/Bikesharing-with-Tableau/blob/main/Reference_Images/Top%20starting%20locations.PNG)
This is a scatter plot which displays the starting location for the bike ride. The location with more bike rides is displayed in darker color and bigger radius.
[link to Tableau visualization](https://public.tableau.com/profile/akshaya1961#!/vizhome/Usertripsbygenderweekday2/TopStartinglocations?publish=yes)

## Summary
### A. The following points are the conclusions from all the visualizations created in this project which can be used as references for different locations.
1. More number of bikes are rented by all genders for a trip duration of 4 hours to 8 hours. This can help set the inventory for the bikes that will be required.
2. More number of bikes are rented by male riders than female riders. Which is approx to three times more by looking at the vizualization. This information can help if the investors want to order different bikes by gender.
3. The most number of bikes rented on a weekday are during morning 7am to 9am and evenings 5pm to 7pm, while on weekends there is a fare number of rental throughout the day from 9am to 7pm. The heat map helps us understand at what time the bikes are rented.This information can be used to stock inventory at a selected time.
4. When the above heat map is distributed by gender we can see a similar pattern which means that the rental times are same. The male riders have a darker color showing more number of rentals.This information can help for stocking inventory as per gender requirements.
5. There is a fare number of rental on each day but looking at the User trips by Gender by weekday vizualization we can conclude that there are more male riders than female riders who are subscribers.
6. Looking at the August data, higher number of bikes are rented between 3pm to 7pm which is a perfect evening time to ride in New York.These stations should have the inventory at these times for a successful business.
7. Top starting locations can help determine which locations need more inventory. The dark colors of the scatter plot will help identifying the stations that have more rentals.
8. We can also find out how many bikes are rented at a particular location for a tripduration.
9. We can also find out how many bikes are rented on a particular day.
10. We can also find out top ten start locations.
11. A lot of questions regarding setting up a new bikesharing business in Des Moines can possibly be answered by looking at the results from the visualizations created by the New York bikesharing data.

### B. Below are the additional visualizations suggested for future analysis
#### 1. Bike count for trip duration:
![](https://github.com/Akshaya-Kamble/Bikesharing-with-Tableau/blob/main/Reference_Images/Bike%20count%20for%20Trip%20duration.PNG)
This bar graph shows multiple data and is filtered to show the top five start locations depending on the bikes rented out.The x axis has the time and the y axis has the count of bikes.Each start station is represented by color and the size of the bar represents how many bikes were rented at that location.The overall bar represents the tripduration.We can conclude that more number of bikes are rented for a tripduaration of six and seven hours at all the five top start locations.
[link to Tableau visualization](https://public.tableau.com/profile/akshaya1961#!/vizhome/Usertripsbygenderweekday2/Bikecountfortripduration?publish=yes)

#### 2. Bike rental by days:
![](https://github.com/Akshaya-Kamble/Bikesharing-with-Tableau/blob/main/Reference_Images/Bike%20rental%20by%20days.PNG)
The pie chart above shows the number of bikes that are rented on different days. The data shows that the highest number of bikes are rented on a thursday followed by friday.
[link to Tableau visualization](https://public.tableau.com/profile/akshaya1961#!/vizhome/Usertripsbygenderweekday2/Bikerentalsbydays?publish=yes)

#### 3. Top ten start stations:
![](https://github.com/Akshaya-Kamble/Bikesharing-with-Tableau/blob/main/Reference_Images/Top%20ten%20start%20stations.PNG)
After filtering the data for the top ten starting locations we can see that the station named "Pershing Square North" has the highest number of bikes rented which counts to 16,564.
[link to Tableau visualization](https://public.tableau.com/profile/akshaya1961#!/vizhome/Usertripsbygenderweekday2/Toptenstartstations?publish=yes)


