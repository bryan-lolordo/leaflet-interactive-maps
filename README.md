# leaflet-interactive-maps

The goal of the project is to display multiple interactive maps with the location and magnitude of earthquakes data to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

The Javascript-Leaflet library, HTML, CSS, Bootstrap, and Javascript were used in the project. The Mapbox-API was also used to load the base maps. 

The project was divided into two steps with different levels of complexity.

## Step 1: Create the Earthquake Visualization
This will be a single base layer and one set of data being used. Gather the dataset from [USGS Site](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) to access the data and use the URL of this JSON to pull in the data for the visualization. Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude including popups and a legend. 

![leaflet-earthquakes](https://github.com/bryan-lolordo/leaflet-challenge/assets/134180762/96606cca-336c-4ee5-8fcc-e9276d0c45ec)

Base layer: mapbox.greyscale <br>
Data Layer Source: United States Geological Survey (USGS)<br>
Data: All Earthquakes for the last 7 days<br>

## Step 2: Map to illustrate the relationship between tectonic plates and seismic activity
An additional dataset and plot were included and they can be activated and deactivated by the user.
Data markers reflects the magnitude of the earthquake by their size and and depth of the earth quake by color. 
Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.
The map includes popups that provide additional information about the earthquake when a marker is clicked.
Legends created that will provide context for the map data.

![leaflet-earthquakes-tectonicPlates](https://github.com/bryan-lolordo/leaflet-challenge/assets/134180762/7cf5150f-961a-4ae4-86ad-a2aa6baab05e)

Base layer:
- mapbox.greyscale
- mapbox.satellite
- mapbox.outdoors

Data: All Earthquakes - Last 7 days <br>
Layer 2: Tectonic Plates <br>
Source: Hugo Ahlenius, GIS-and-Cartography Consultant https://github.com/fraxen/tectonicplates
Libraries Required (already included in the index.html file)
D3 JavaScript, Leaflet


## Instructions Steps

- Download or clone all the files contained in this repo.
- Create a Mapbox Token
- Include your Mapbox Token in the /Leaflet-Step-1/static/js/config.js and /Leaflet-Step-2/static/js/config.js files.
- Run a python -m http.server or any other method for this purpose.
- Load the Leaflet-Step-1/index.html and Leaflet-Step-2/index.html files.
