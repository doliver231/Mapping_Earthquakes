# Mapping_Earthquakes

## Project Overview

The objective of this project is to gather earthquake GeoJSON data from the USGS API, create, and explore interactive maps of earthquakes around the world. The earthquake data is represented on the maps in relation to the tectonic plates’ location on the earth, and according to each event's magnitude.

## Resources

* Data Source: [Earthquakes GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson), [Major Earthquakes >4.5mag GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson), [Tectonic Plate GeoJSON](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
* Software: HTML/CSS, JavaScript, Visual Studio Code, Leaflet 1.7.1, D3.js, Mapbox

### Interactive Maps Views

Base Layer "Streets" and Overlay Layer showcasing "All Earthquakes" are selected:

![Streets](https://github.com/doliver231/Mapping_Earthquakes/blob/main/Images/Streets-AllEarthquakes.png)

Base Layer "Satellite" and Overlay Layer showcasing "Tectonic Plates" are selected:
![Satellite](https://github.com/doliver231/Mapping_Earthquakes/blob/main/Images/Satellite-Tectonic.png)

Base Layer "Dark" and Overlay Layer showcasing only "Major Earthquakes with magnitude above 4.5" are selected:
![Dark](https://github.com/doliver231/Mapping_Earthquakes/blob/main/Images/Dark-MajorEarthquakes.png)