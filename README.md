## Title: Thomas Fire Temporal and Spatial Analyses: Air Quality Timeseries and False Color Image of Infrared

## Purpose of Repository

The purpose of these analyses are to look at the impacts of the Thomas Fire on Santa Barbara County. This fire occurred in December 2017 and continued through mid January 2018. We are looking into how the Air Quality Index may have changed throughout 2017 and 2018 in relation to the fire, and we are looking at in relation to the geographic location of the fire by overlaying the Thomas fire perimeter over a false color image of the surrounding area to look at the short-wave infrared (swir22) and near-infrared values. 

## Highlights of analyses
- Import and clean timeseries data using pandas
- Calculate a rolling average over a 5 day rolling window
- Visualize the average AQI and AQI readings over time, specifying colors using a dictionary
- Import and clean raster and shapefile data using rasterio and geopandas
- Change Coordinate Reference System (crs) to ensure the raster and shapefile match
- Create a False Color Image by overlaying three variables of interest and the fire boundary shapefile
- Customizing a plot using matplotlib's pyplot and mpatches to create an aesthetically pleasing legend

## Data Citations: 

United States Environmental Protection Agency Air Data (2023), *daily_aqi_by_cbsa_2017.zip* [Data file] Available from: https://aqs.epa.gov/aqsweb/airdata/download_files.html#AQI. Access date: 11.27.2023. 

United States Geological Survey Landsat Missions hosted by Microsoft Planetary Computer (2023), *Landsat Collection 2 Level-2* [Data file] Available from: https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2. Access date: 11.27.2023. 

California Department of Forestry and Fire Protection (2023), *California Fire Perimeters (all)* [Data file] Available from: https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all-1/about. Access date: 11.27.2023. 
