# STA523 Final Project
This repo contains the code for my team final project on predicting and visualizing the number of red light camera violations in the Chicago city using R. The code is in the file "FinalProject.Rmd", run the code to activate the Shiny app that presents our project. Steps in our analysis are listed below:

Gather Data:
-	Traffic Data for the city of Chicago
    * https://dev.socrata.com/foundry/data.cityofchicago.org/8v9j-bter 
    * https://data.cityofchicago.org/resource/8v9j-bter.json  
-	Red light camera data 
    * https://data.cityofchicago.org/Transportation/Red-Light-Camera-Violations/spqx-js37 
-	Darksky weather data
    * (Darksky API) 

Generate Prediction, variables will include:
   * Daily Traffic
   * Weather 
   * Temperature
   * Visibility
   * Precipitation
   * Accumulation of snow
   * Intersection
   * Day of the week
   * Month
   * Latitude / Longitude

Outcome Variable
   * Red Light Camera Violations

Objective:
   * Find intersections without redlight cameras, but with traffic data
   * Predict Red Light camera Violations for intersections without red light camera

Shiny App
-	User picks date in the past and we show actual and predicted red light camera violations for that day
