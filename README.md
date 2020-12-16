# Comparing Crime Rates & Hotel Ratings

Is there any correlation between crime and hotel rating?  

## Table of Contents 
* [Team Name](#Team_Info)   
* [Overview](#overview) 
* [Datasets](#Datasets) 
* [Tasks](#tasks)
* [Technologies](#technologies) 
* [Setup](#setup)  
* [Summary](#summary)  

## Team Name: Project Won
## Members:
Meghan Luoma, Kirby Miller, Sara Riggs, Alicia Perez, and Kerry Wehner  

## GitHub URL: 
https://github.com/meghanvl/project_won.git

## Overview 
The purpose of this project is to determine if there is a correlation between crime and hotel ratings in Kansas City, MO; New Orleans, LA; Dallas, TX; Portland, OR; Charlottesville, VA; Chicago, IL; Denver, CO; Sioux Falls, SD; Las Vegas, NV; San Francisco, CA; Chattanooga, TN; and Boston, MA in 2019.  

Question 1: Is there any correlation between average hotel ratings and crime rating? 
Question 2: Is there any correlation between a city's population and crime rate? 
Question 3: Is there any correlation between a city's population and average hotel rating?  

Hypothesis: Cities with greater populations will have higher crime rates than cities with smaller populations, and cities with higher crime rates will have lower average hotel ratings.

## Datasets: 
* [City Coordinates](https://latitudelongitude.org/us/)  
* [Charlottesville, CA Coordinances](https://www.lat-long.com/Latitude-Longitude-1498463-Virginia-Charlottesville.html)  
* [Crime Data API](https://crime-data-explorer.fr.cloud.gov/api)  
* [ORI Lookup Table (provided by: ICPSR)](https://www.icpsr.umich.edu/files/NACJD/ORIs/STATESoris.html)  
* [Population Data](https://github.com/CommerceDataService/census-wrapper)  
* [Population Labels](https://gist.github.com/afhaque/60558290d6efd892351c4b64e5c01e9b)  
* [Hotel Reviews Using Google Places Library](https://developers.google.com/maps/documentation/javascript/places)  


## Tasks
Alicia - API dataset pull<br>
Sara - API dataset pull<br>
Kirby - Crimeometer data pull, Matplotlib<br>
Kerry - Matplotlib<br>
Meghan - linear regression<br>


## Technologies
Project is created with:  
* Pandas 1.0.5  
* Jupyter Notebook 4.6.3  
* Matplotlib 3.3.2  

## Setup
To run the code, open it with jupyter Notebook.
For running the jupyter notebook files the following is required:
* Pip install of gmaps  
* Pip install of citypy  
* Census Key   
* Google Key  
* Crime Data Key (please see the Crime Data API website listed above)

## Summary
There is no observable correlation between hotel rating and crming rating. 
