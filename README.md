# Toronto Real Estate Investment 
PyViz Assignment - Pythonic Monopoly,
building a prototype dashboard to analyze the Toronto Real Estate market.

<img src= https://github.com/ChantalAG/PyViz-Homework/blob/main/Toronto.jpg height = 400, width = 800>

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
* Mapbox API

## Instructions
The first step to building the dashboard is to work out all of the calculations and visualizations in an [analysis notebook](). Once the code was running properly, it was copied over to a [dashboard code]() and used with Panel to create the final layout. 

**In the dashboard you can navigate through the tabs to find the following information on Toronto Real Estate from 2001 to 2016:**

### Welcome: 
Here you will find an interactive Neighbourhood Map with the average prices per neighbourhood.\
Use the **zoom feature** to locate specific areas. 

![image](https://user-images.githubusercontent.com/99493522/162515975-63db54a7-7b18-4450-821f-c16ced328009.png)


### Yearly Analysis: 
The number of dwelling types per year from the years 2001, 2006, 2011 and 2016 presented as bar charts.


![image](https://user-images.githubusercontent.com/99493522/162516249-015288d0-940a-4140-b8e1-2bb4eec53baa.png)
![image](https://user-images.githubusercontent.com/99493522/162515788-112d92a1-4f45-466c-a4bf-8cf7958de78d.png)
![image](https://user-images.githubusercontent.com/99493522/162516149-d19e9c52-0f1c-4779-ba53-055c129916a7.png)
![image](https://user-images.githubusercontent.com/99493522/162515899-c43fba0b-4fdb-4335-a5f7-96ab41b8c961.png)



 
### Shelter Analysis: 
Average monthly shelter costs in Toronto per year.
Line charts provided allow you to visualize the average (mean) shelter cost for owned and rented dwellings per year to understand rental income trends over time. 

![image](https://user-images.githubusercontent.com/99493522/162515405-c74b0919-1298-4c68-9333-21274a06371f.png)
![image](https://user-images.githubusercontent.com/99493522/162515352-cdcf5974-7a5f-47ed-8d66-75f553300093.png)

### Neigbourhood Analysis:
Average house value per year presented as a line chart for an investor to better understand the sales price of the rental property over time. 

![image](https://user-images.githubusercontent.com/99493522/162516498-db31eee0-0a86-4cc0-baa1-f1cd8d1654da.png)

Average prices by neighbourhood presented as an interactive line chart that compares house values by neighbourhood.\
**Use the drop down box to select the desired neighbourhood.** 

![image](https://user-images.githubusercontent.com/99493522/162516550-3b192388-c33f-4cd3-9d9e-ec229ed7ce64.png)

Number of dwelling types per year per neigbourhood presented as an interactive bar chart to provide investors a tool to understand the evolution of dwelling types over the years.
**Use the drop down box to select the desired neighbourhood.**



![image](https://user-images.githubusercontent.com/99493522/162516612-db5b773b-fbf0-4659-aa81-0a676a2246ec.png)


### Most Expensive Neighbourhoods: 
The top 10 most expensive neighbourhoods are presented as a bar chart. **Hover over the bars to reveal more information.**

The mean house value for each neighbourhood was calculated and then sorted to obtain the top 10 most expensive neighbourhoods on average. 

![image](https://user-images.githubusercontent.com/99493522/162515631-15832f09-28f1-4b78-a937-fe77c2e64cf8.png)

### Issues
Some of the main dashboard tabs did not run successfully. 

## Contributors
Chantal Garnett
