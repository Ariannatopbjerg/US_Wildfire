# Project notes

# Data exploration
Use TablePlus for SQLite files
FPA_FOD_20170508.sqlite - contains many empty sets
Valid data - fires but I can't seem to export the data
Other data - idx* files related to fire shape

Should review FW_Veg_Rem_Combined.csv then determine if we need more data

Questions are more human based, may need to reword for machine learning

We can use a time series (fintech), ask the TAs for help

## Visualization options
HTML with flask app where user input feeds to model (she can help with this)
Tableau ok

## For other datasets check gov sites, if data not published we can contact them directly

Entire US may be too large, consider only California or combination of western 
states like CA & Oregon or CA, Oregon and Washington

Sites to check out.
https://blogs.sas.com/content/sascom/2018/06/29/blazing-statistics-visualizing-wildfire-data/

https://anychart.medium.com/california-wildfire-in-maps-and-charts-dataviz-weekly-b726f4245972

https://towardsdatascience.com/visualizing-the-2017-wildfire-season-2053fe72525f

https://www.psehealthyenergy.org/our-work/interactive-tools/california-wildfire/

https://west.stanford.edu/projects/ecowest-environmental-data-visualizations

https://machinelearningmastery.com/probability-metrics-for-imbalanced-classification/

https://github.com/pandas-profiling/pandas-profiling

YouTube video on Exploratory data analysis in python - PyCon 2017
https://www.youtube.com/watch?v=W5WE9Db2RLU
https://github.com/cmawer/pycon-2017-eda-tutorial

Found this one as well - it has multiple links.
https://inciweb.nwcg.gov/links/

## Machine Learning Model Brainstorm:
Supervised learning: Random Forest or Decision Trees (compare both models for best fit)
Model Features:
Weather (Humidity, Precipitation, Wind, Temperature)
Lat/Long
Population density per county
Type of fire
