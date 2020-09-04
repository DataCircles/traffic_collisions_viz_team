
![image](https://user-images.githubusercontent.com/61078217/92278821-de522d80-eeaa-11ea-85b6-7c4586f23508.png)

# Traffic Collision Data Visualization Project

This is the public repository containing the Traffic Collisions Project materials for the Data Visualization Team. The Data Visualization Team was part of the larger Data Circles six week project analyzing Seattle area traffic collision data collected by the Seattle Dept. of Transportation (SDOT) over the years, 2004 - 2020.

## Presentation

The project will be presented on September 15, 2020 virtually. The intended audience are Seattle policymakers.

## Team Members:

- Niwako Sugimura  
- Jeny De Figiueiredo  
- Monika Helak  
- Rebecca Stewart  
- Jamie Shaffer

## Data Sources

![image](https://user-images.githubusercontent.com/61078217/92277985-148ead80-eea9-11ea-8bbd-6335cdac17a0.png)

We started out with the dataset of collisions over the period 2004-2020 from the Seattle Department of Transportation. For greater insight, we merged other datasets of Seattle Traffic data over the same time period. Due to the nature our of project and its significant mapping emphasis, we dropped observations from the original that were missing x,y coordinate data. We also did not include data from 2020 in our analysis.

Links to sources of external datasets:



## Project Process

Our project process what divided into two phases. 

Phase I included data wrangling and exploration of various sources of Seattle Traffic Data. The end result was exporting a finalized collisions_clean.csv in our data folder that we all commonly imported into Tableau. The notebooks folder contains all elements of this process.

Phase II included putting together a Story in Tableau. We identified the five most severe collision problem areas in Seattle based on our own calculation of Severity: SEV = (# of collisions) x (accident severity: scale 1-3) 
From these five problem areas, we chose X specific locations to feature on a separate dashboard, analyzing in detail what makes these locations dangerous. Based on our analysis, we came up with tailored recommendations to improve traffic safety in these particular areas.


## Final Project 
The final project is available for viewing on Tableau Public:

https://public.tableau.com/profile/rebecca.stewart#!/vizhome/SeattleProblemAreasandLocationsbySeverityofCollisions/SeattleProblemAreasAnalysisofCollisionsbyLocation?publish=yes
