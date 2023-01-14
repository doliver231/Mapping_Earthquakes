# Mapping_Earthquakes

## Project Overview

The objective of this project is to gather earthquake GeoJSON data from the USGS API, create, and explore interactive maps of earthquakes around the world. The earthquake data is represented on the maps in relation to the tectonic plates’ location on the earth, and according to each event's magnitude.

## Resources

* Data Source: [Earthquakes GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson), [Major Earthquakes >4.5mag GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson), [Tectonic Plate GeoJSON](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
* Software: HTML/CSS, JavaScript, Visual Studio Code, Leaflet 1.7.1, D3.js, Mapbox

## Analysis

To interact with the maps API, the user has to create a Mapbox account on the [website](www.mapbox.com) and retrieve the access token.

As shown below, the [index.html]() calls for the Mapbox API key in the `config.js` file.

![config html]()
![config Static]()

To open the `index.html` file: open the command line, navigate to the main directory, and enter:

                            ```py
                            python -m http.server
                            ```

### Interactive Maps Views

The deployed webpage is accessible at https://doliver231.github.io/Mapping_Earthquakes.

Base Layer "Streets" and Overlay Layer showcasing "All Earthquakes" are selected:

![Streets]()

Base Layer "Satellite" and Overlay Layer showcasing "Tectonic Plates" are selected:
![Satellite]()

Base Layer "Dark" and Overlay Layer showcasing only "Major Earthquakes with magnitude above 4.5" are selected:
![Dark]()