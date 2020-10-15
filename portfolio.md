---
layout: page
title: Portfolio
permalink: /portfolio/
---


## Data Science projects

- **Microtransit and its Impact on Communities within the US**\| [GitHub repo](https://github.com/jackblobe/Spare_Ridership)
    - Investigated the impact of microtransit within the US using ridership data from Spare Labs inc. 
    - Created GeoJsons out of census data to fence riders into census block groups
    - visualized data using Kepler, Folium and Seaborn
    - Created a time series forcast, and wait time predictor for riders.
    - Currently constructing deep spatio temporal demand forcast. 

- **Climate Model** \| [GitHub repo](https://github.com/jackblobe/Climate_Models_ENVR400)
    - Completed as part of capstone project to study vegitation patters within Burns Bog.
    -Using CESM data, I created change of temperature and precipitation predictions for the pacific northwest, at the finest resolution available. 
    -Coupling this with data collected on site, used DBSCAN to identify clusters of boundary zones and predicted how it will change with the climate. (cannot comit the R code for this, now part of UBC environmental science program, but full essay can be see here: [Publication](https://open.library.ubc.ca/cIRcle/collections/undergraduateresearch/52966/items/1.0390363)
    - Status: Complete


- **Flight Delay Predictor and Classifier** \| [GitHub repo](https://github.com/jackblobe/FlightDelayPrediction)
    - Using randomforest regression predicted delay for flights in Janurary of 2020 within the United states. EDA was can be seen in exploratory analysis notebook.  
    - Status: Complete
    - Given error within the model, tying in time series into delay would be a useful way to reduce error. Futher, given the size of the data set, deep learning with tensor dimensions being grids of the US with given size in km could provide a more accurate prediction given the features created. 
    - Classifier bias reduced through bootstrapping and SMOTE, in the end, as it often does for my projects, bootstrapping created better predictions with less of a bias variance trade off.  


