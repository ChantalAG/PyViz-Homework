# Toronto Real Estate Investment 
PyViz Assignment - Pythonic Monopoly,
building a prototype dashboard to analyze the Toronto Real Estate market.

img < 

## Background
The goal of this dashboard is to provide charts, maps, and interactive visualizations that help customers explore the data and determine if they want to invest in rental properties in Toronto. 

The data provided for this assignment was retrieved from the following websites:

* [Toronto Open Data](https://open.toronto.ca/)
* [Census Profile, 2016 Census - Toronto Metropolitan Area, Ontario and Canada](https://www12.statcan.gc.ca/census-recensement/2016/dp-pd/prof/details/page.cfm?Lang=E&Geo1=CMACA&Code1=535&Geo2=PR&Code2=01&SearchText=toronto&SearchType=Begins&SearchPR=01&B1=All&TABID=1&type=0)

## Resources
* toronto_neighbourhoods_census_data.csv
* toronto_neighbourhoods_coordinates.csv


## Technologies
* Jupyter Notebook
* Python
* Pandas
* Panel
* Mapbox API

## Instructions
The first step to building the dashboard is to work out all of the calculations and visualizations in an [analysis notebook](). Once the code was running properly, it was copied over to a [dashboard code]() and used with Panel to create the final layout. 

**In the dashboard you can navigate through the tabs to find the following information on Toronto Real Estate from 2001 to 2016:**

### Welcome: 
Here you will find an interactive Neighbourhood Map with the average prices per neighbourhood.\
Use the **zoom feature** to locate specific areas. 

### Yearly Analysis includes: 
The number of dwelling types per year from the years 2001, 2006, 2011 and 2016 presented as bar charts.
 
### Shelter Analysis includes: 
Average monthly shelter costs in Toronto per year.
Line charts provided allow you to visualize the average (mean) shelter cost for owned and rented dwellings per year to understand rental income trends over time. 

### Neigbourhood Analysis includes:
Average house value per year presented as a line chart for an investor to better understand the sales price of the rental property over time. 

Average prices by neighbourhood presented as an interactive line chart that compares house values by neighbourhood.\
**Use the drop down box to select the desired neighbourhood.** 

Number of dwelling types per year per neigbourhood presented as an interactive bar chart to provide investors a tool to understand the evolution of dwelling types over the years.\
**Use the drop down box to select the desired neighbourhood.**

### Most Expensive Neighbourhoods 
The top 10 most expensive neighbourhoods are presented as a bar chart. **Hover over the bars to reveal more information.**

The mean house value for each neighbourhood was calculated and then sorted to obtain the top 10 most expensive neighbourhoods on average. 

## Contributors
Chantal Garnett
