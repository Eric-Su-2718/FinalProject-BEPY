
Gather Data:
-	Traffic Data for the city of Chicago
    * https://dev.socrata.com/foundry/data.cityofchicago.org/8v9j-bter 
    * https://data.cityofchicago.org/resource/8v9j-bter.json  
-	Red light camera data 
o	https://data.cityofchicago.org/Transportation/Red-Light-Camera-Violations/spqx-js37 
-	Darksky weather data
o	(Darksky API) 

Generate Prediction Dataset
-	Variables will include:
o	Daily Traffic
o	Weather 
♣	Temperature
♣	Visibility
♣	Precipitation
♣	Accumulation of snow
o	Intersection
o	Day of the week
o	Month
o	Latitude/Longitude

-	Outcome Variable
o	Red Light Camera Violations

-	Objective:
o	Find intersections without redlight cameras, but with Traffic data
o	Predict Red Light camera Violations for intersections without red light camera

Shiny App
-	User Picks Date in the past and we show actual and predicted red light camera violations for that day
