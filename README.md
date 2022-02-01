Visualization of Earthquake data from US Geological survey using Javascript Leaflet.js library, Javascript, and HTML

# Mapping Earthquakes

# Project Overview
GeoJSON earthquake data was pulled from the USGS website to retrieve the geographical coordinates and magnitudes of earthquakes for the last seven day and create interactive maps of earthquakes around the world. The earthquake data is represented on the maps in relation to the tectonic plates’ location on the earth, and according to each event's magnitude.

**Note:** Needs an API key for accessing maps. Visit [mapbox.com](https://www.mapbox.com/), create a Mapbox account and retrieve the access token.

# Resources
* **Data Source:** Earthquakes GeoJSON, Earthquakes above 4.5mag GeoJSON, Tectonic Plate GeoJSON
* **Software:** HTML/CSS, JavaScript, Visual Studio Code 1.49.1, Leaflet 1.7.1, D3.js 6.2.0

# Results

Code for final deloyment in [earthquake_challenge](https://github.com/ramya-ramamur/Mapping_Earthquakes/tree/main/earthquake_challenge) folder.

* The map displays all earthquake data over the past 7 days and the tectonic plates are located around the world.
* Each earthquake and each lineString of tectonic plates boundary will have a popup marker that, when clicked, will show the information.
* You can choose to toggle the map view from 3 different styles: Street View, Satellite Street View, and Night Navigation modes.
* On the upper right side of map, a layer control allows users to control which overlays (Earthquakes, Tectonic Plates, Major Earthquakes)they see on map.

**Streets View**

![57F161D4-F9AE-4F05-A684-C0EDC3D25F2B_1_201_a](https://user-images.githubusercontent.com/75961057/151754598-71a19005-2bb4-4ea9-9b28-b4dc37c47ffb.jpeg)

**Satellite Street View**

![020062BE-B653-422E-A325-F237E67665A6_1_201_a](https://user-images.githubusercontent.com/75961057/151754679-1497b740-4708-4a64-a5b3-df86ff5b2c23.jpeg)

**Night Navigation View**

![79F31E25-EED7-4BA8-B1A1-C62E228E1FB3_1_201_a](https://user-images.githubusercontent.com/75961057/151754752-e7354344-4fcb-4f3a-ba41-3915f25f98af.jpeg)
