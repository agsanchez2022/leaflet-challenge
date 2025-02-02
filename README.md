# Leaflet Challenge

## Background
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## Before You Begin
1. Create a new repository for this project called `leaflet-challenge`. Do not add this Challenge to an existing repository.
2. Clone the new repository to your computer.
3. Inside your local git repository, create a directory for the Leaflet challenge. Use the folder names to correspond to the challenges: `Leaflet-Part-1` 
4. This Challenge uses both HTML and JavaScript, so be sure to add all the necessary files. These will be the main files to run for analysis.
5. Push the above changes to GitHub.

### Create the Earthquake Visualization
Task is to visualize an earthquake dataset. Complete the following steps:

1. **Get your dataset.** To do so, follow these steps:
   - The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson) page and choose a dataset to visualize.

2. **Import and visualize the data by doing the following:**
   - Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.
   - Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color. (Hint: The depth of the earth can be found as the third coordinate for each earthquake.)
   - Include popups that provide additional information about the earthquake when its associated marker is clicked.
   - Create a legend that will provide context for your map data.

Your visualization should look something like the preceding map.





