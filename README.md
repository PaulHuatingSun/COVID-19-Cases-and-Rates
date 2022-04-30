# COVID-19-Cases-and-Rates
Huating Sun \
GEOG 458 Section AB \
Lab 3: Web Map Application \
April 29, 2022

## Project Introduction
This project includes two maps using county level COVID-19 data. Map 1 is a choropleth map of COVID-19 rates in the United States by county. Map 2 is a proportional symbols map of COVID-19 cases in the United States by county.


## Maps Link
- [Map 1: Choropleth Map of COVID-19 Rates in the United States by County](https://paulhuatingsun.github.io/COVID-19-Cases-and-Rates/map1.html)
- [Map 2: Proportional Symbols Map of COVID-19 Cases in the United States by County](https://paulhuatingsun.github.io/COVID-19-Cases-and-Rates/map2.html)

## Map Screenshots
Map 1: Choropleth Map of COVID-19 Rates in the United States by County
![Map 1](/img/map1.png "Map 1") 

Map 2: Proportional Symbols Map of COVID-19 Cases in the United States by County
![Map 2](/img/map2.png "Map 2") 

## Primary Map Functions
- The primary function of the first map is the information window located in the upper left corner of the map. When the cursor is hovering over a county, the information window displays the COVID-19 rate information in that specific county and shows which state that county is in. If the cursor is not hovering over a county, the window will display "Place Mouse to See the COVID-19 Rate for a County."
- The primary function of the second map is the clickable data points. Once a data point is clicked on, the number of COVID-19 cases and the county name will be displayed.


## Libraries Used
- [Map Box API](https://docs.mapbox.com/api/overview/)
- [JavaScript](https://www.javascript.com/)

## Data Sources
- [The New York Times](https://github.com/nytimes/covid-19-data/blob/43d32dde2f87bd4dafbb7d23f5d9e878124018b8/live/us-counties.csv)
- [2018 ACS 5 year estimates](https://data.census.gov/cedsci/table?g=0100000US.050000&d=ACS%205-Year%20Estimates%20Data%20Profiles&tid=ACSDP5Y2018.DP05&hidePreview=true)
- [The U.S. Census Bureau](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html)

## Credits
- [MapShaper](https://mapshaper.org/)
- [MapBox](https://docs.mapbox.com/mapbox.js/api/v3.3.1/)
- [Color Designer](https://colordesigner.io/gradient-generator)
- [Map Box Mouse Pointer Tutorial](https://docs.mapbox.com/mapbox-gl-js/example/queryrenderedfeatures/)
- [Github Tutorial Made by Professor Bo Zhao](https://github.com/jakobzhao/geog458/tree/master/labs/lab03)

## Acknowledgments
Thank you Jiaxin Feng and Steven Bao for their assistance!
