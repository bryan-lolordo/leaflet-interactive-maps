# leaflet-interactive-maps

The goal of the project is to display multiple interactive maps with the location and magnitude of earthquakes data to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

The Javascript-Leaflet library, HTML, CSS, Bootstrap, and Javascript were used in the project. The Mapbox-API was also used to load the base maps. 

The project was divided into two steps with different levels of complexity.

## Step 1: Create the Earthquake Visualization
This will be a single base layer and one set of data being used. Gather the dataset from [USGS Site](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) to access the data and use the URL of this JSON to pull in the data for the visualization. Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude including popups and a legend. 

![leaflet-earthquakes](https://github.com/bryan-lolordo/leaflet-challenge/assets/134180762/96606cca-336c-4ee5-8fcc-e9276d0c45ec)

Layer 1: Earthquakes
Data Source: United States Geological Survey (USGS)

## Step 2: Map to illustrate the relationship between tectonic plates and seismic activity
An additional dataset and plot were included and they can be activated and deactivated by the user.
Data markers reflects the magnitude of the earthquake by their size and and depth of the earth quake by color. 
Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.
The map includes popups that provide additional information about the earthquake when a marker is clicked.
Legends created that will provide context for the map data.

![leaflet-earthquakes-tectonicPlates](https://github.com/bryan-lolordo/leaflet-challenge/assets/134180762/7cf5150f-961a-4ae4-86ad-a2aa6baab05e)

Layer 2: Tectonic Plates
Source: Hugo Ahlenius, GIS-and-Cartography Consultant - [techtonicplates repository](https://github.com/fraxen/tectonicplates)
Libraries Required (already included in the index.html file)
D3 JavaScript, Leaflet
