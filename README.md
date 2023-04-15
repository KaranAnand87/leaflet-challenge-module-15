# leaflet-challenge-module-15

The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, I have developed a way to visualize USGS data that will allow USGS to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

In order to visualize an earthquake dataset. I have completed the following steps:

1. The USGS provides earthquake data in a number of different formats, updated every 5 minutes. I visited the USGS GeoJSON Feed Links to an external site. page and chose a dataset to visualize. T

2. I clicked on a dataset (such as "All Earthquakes from the Past 7 Days"), to get a JSON representation of that data. I have used the URL of this JSON to pull in the data for the visualization. 

3. Using Leaflet, I created a map that plots all the earthquakes from your dataset based on their longitude and latitude.

4. The data markers reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes appear larger, and earthquakes with greater depth appear darker in color.

5. I have included popups that provide additional information about the earthquake when its associated marker is clicked.

6. I have created a legend that will provide context for the map data.
