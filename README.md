# MMM
## Geo-spacial Analysis of Payday Loan Lenders in Impoverished California Communities
### Description
This repository hosts a geo-spatial analysis of the locations of impoverished communities across California and their relation to  paydaylender locations in California. Data sources for this project include: 
/* U.S. Census Bureau American Community Survey (ACS5) API (for data on Poverty across California)
/* Google Maps API (for "Payday lender" locations)
#### Research Question
Do payday lenders target impoverished communities? 
#### Subquestions: 
Do covariables such as race/ethnicity of impoverished communites explain where payday lenders set up shop? 

### What is in this Repository:

This repository can be broken down into 2 parts: 
1.) Payday lender geographical coordinate data cleanup and analysis, 
Associated files: 
    *paydayloanvendor.ipyn (contains code pulling payday vendor location from google maps api)
    *paydaymergeviz (contains code that merges payday lender locations and zip code information for combined data sets)
    *resources folder
        *IS_cleaning (contains code cleaning payday lender location by filtering out traditional banking institutions) 
        data was written to csv files in "Resources" folder
    
2.) U.S. Census poverty data cleanup, analysis and visualization, Associated files: 
    * Census data API pulling and workup is found in the directory '/census_data_maps'
    * 'Census_PovertyData' (contains code pulling census poverty data by zipcode)
    *choropleth maps.ipyn (contains code merging, cleaning and visualizing all data sources with Choropleth maps)
    */resources directory contains csv files of written output from census API and PNG image files of visualizations
    

### Technical Requirements
This analysis was performed in using Python in Jupyter Notebooks.
Libraries used: 
Pandas, Numpy, Scipy Stats, Matplotlib, Geopandas and Shapely

### Final Report

The MMM.2.pptx file contains the final presentation of the findings in this analysis. 
