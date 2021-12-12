The dataset we plan to implement has been obtained from NYC Open Data. It is a comprehensive dataset with 29 columns and 1.8 million data rows. The link to the dataset is [Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95).

This [Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95) crash table contains details on the crash event. The Motor Vehicle Collisions data tables has every row describing a motor vehicle collision and it contains information from all police reported motor vehicle collisions in NYC.

Note - A police report MV104-AN is required to be filled out for collisions where someone is injured or killed, or where there is at least $1000 worth of damage can be checked [here](https://www.nhtsa.gov/sites/nhtsa.dot.gov/files/documents/ny_overlay_mv-104an_rev05_2004.pdf).

Through this project, we would like to answer the following questions with Exploratory Data Analysis and Visualization:

* What time during the day has majority of accidents? Medical Services and the NYPD could be more vigilant at this time. Columns that may be used: CRASH DATE, CRASH TIME
* Which localities are most accident-prone? Columns that may be used: BOROUGH, ZIP CODE, LATITUDE, LONGITUDE, LOCATION, all 8 columns with NUMBER INJURED AND KILLED.
* Which areas are most dangerous for pedestrians at night-time? It would be wiser to avoid such areas. Columns that may be used: BOROUGH, ZIP CODE, LATITUDE, LONGITUDE, LOCATION, NUMBER OF PEDESTRIANS INJURED, AND NUMBER OF PEDESTRIANS KILLED.
* What are leading contributors to accidents in accident-prone areas? Also, which of these factors would lead to the most fatal accidents? Columns that may be used: All 8 columns with NUMBER INJURED AND KILLED, CONTRIBUTING FACTORS 1 – 5, VEHICLE TYPE CODE 1 – 5.
* What vehicle types are involved in the maximum number of fatal accidents? Columns that may be used: All 8 columns with NUMBER INJURED AND KILLED, CONTRIBUTING FACTORS 1 – 5, VEHICLE TYPE CODE 1 – 5.
* Analyzing data from 2012, was there a drop in the accidents in any area? Clearly, the measures taken to tackle accidents there would have worked. Columns that may be used: BOROUGH, ZIP CODE, LATITUDE, LONGITUDE, LOCATION All 8 columns with NUMBER INJURED AND KILLED, CONTRIBUTING FACTORS 1 – 5.

We hope that such visualizations would help draw inferences that could help reduce the collisions on road.


*This repo was initially generated from a bookdown template available here: https://github.com/jtr13/EDAVtemplate.*	
