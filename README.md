# LEarthquake plotting and visualiztion

## Background

![1-Logo](Images/1-Logo.png)

Welcome to the United States Geological Survey, or USGS for short. The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.


We will use this data to visualize earthquakes on the globe.

   ![3-Data](Images/3-Data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize.
   ![4-JSON](Images/4-JSON.png)

We create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

The data markers should reflect the magnitude of the earthquake by their size and and depth of the earthquake by color. Earthquakes with higher magnitudes will appear larger and earthquakes with greater depth will appear darker in color.
