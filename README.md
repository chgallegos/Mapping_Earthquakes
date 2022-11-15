# Mapping_Earthquakes
## Overview

The purpose of this project was to create a map with earthquake data and to add layers for efficient user utilization. In this case the layers added were: Tectonic Plates, Latest Major Earthquakes, and a dark version of the map.


![Screenshot](https://github.com/chgallegos/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/resources/deli1.png)

----
## Results

The project was divided into 3 parts 

#### 1) Tectonic Plate Data
#### 2) Major Earthquake Data
#### 3) Add an Additional Map

### Tectonic Plate Data

The process to create the tectonic plate data was the following: Pass the tectonic plate data to the geoJSON() layer. Style the lines with a color and weight that will make it stand out on all maps. Add the tectonic layer group variable you created in Step 1 to the map, i.e., .addTo(tectonicPlates) and close the geoJSON() layer. Next, add the tectonic layer group variable to the map, i.e, tectonicPlates.addTo(map). Finally, close the d3.json() callback.

This is shown in the following screenshot of the js code:

![Screenshot](https://github.com/chgallegos/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/resources/layers.png)

![Screenshot](https://github.com/chgallegos/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/resources/layers2.png)

![Screenshot](https://github.com/chgallegos/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/resources/retrieve_geojson.png)


### Added a dark layer

Using mapbox, found a street dark template added to the URL and provided the last map which has a dark format and a satellite type of view


![Screenshot](https://github.com/chgallegos/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/resources/deli2.png)

