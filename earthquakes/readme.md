# Earthquake Data
The earthquakes displayed are from the AZGS Earthquake Catalog, and are the minimum number of earthquakes that have occurred in the historical period dating to about 1850.

## Folder contents:

- __earthquakedata.geojson__ [_view_](https://github.com/azgs/hazard-data/blob/master/earthquakedata/earthquakedata.geojson) | [_download_](http://azgs.github.io/hazard-data/earthquakedata/earthquakedata.geojson) : Geographic data representing the locations of earthquake epicenters in Arizona in [GeoJSON format](http://geojson.org).
- __earthquakedata.csv__ [_view_](https://github.com/azgs/hazard-data/blob/master/earthquakedata/earthquakedata.csv) | [_download_](http://azgs.github.io/hazard-data/earthquakedata/earthquakedata.csv) : Another representation of the geographic data in CSV format.
- __earthquakedata.zip__ [_download_](http://azgs.github.io/hazard-data/earthquakedata/earthquakedata.zip) : A zipped folder containing the geographic data in shapefile format.
- __metadata.xml__ [_download_](http://azgs.github.io/hazard-data/earthquakedata/metadata.xml) : Formal ISO 19139 metadata describing this geographic dataset.

## This is a snapshot of a dynamic dataset

The AZGS earthquake data catalog is updated regularly. The data available in this repository was last cached on Sep. 17th, 2013. For the most up-to-date data, please download from one of the following links:

- [_GeoJSON_](http://data.azgs.az.gov/quakedb/earthquakedata.geojson)
- [_CSV_](http://data.azgs.az.gov/quakedb/earthquakedata.csv)
- [_ESRI Shapefiles_](http://data.azgs.az.gov/arizona/azgs/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=azgs:earthquakedata&outputFormat=SHAPE-ZIP)

## Further Reading:

The earthquakes displayed are from the AZGS Earthquake Catalog, and are the minimum number of earthquakes that have occurred in historical times. Older events are represented by estimated Modified Mercalli Intensity Scale (MMI) roman-numeral values which reflect the amount of shaking experienced by those who felt and reported the earthquake. For a full description of the MMI scale, please refer to: http://earthquake.usgs.gov/learn/topics/mercalli.php

The earthquake layer in the AZGS Hazard Viewer includes an epicentral location denoted in Latitude and Longitude, depth (in kilometers), date and time (UTC; -7:00 for MST). There are several magnitude scales employed to estimate the size (i.e., energy release) of an earthquake, such as Md - duration magnitude, ML - local magnitude, Mw - moment magnitude. AZGS calculates duration magnitude, Md; however, the catalog includes all three types of magnitude scales depending on who located the event. For example, northern Arizona earthquakes located by the University of Utah are frequently assigned a local magnitude (Ml). Sources of earthquake data reported in the AZGS Earthquake Catalog, include: AZGS (Arizona Geological Survey), USGS (United States Geological Survey), AEIC (Arizona Earthquake Information Center), UU (University of Utah), CI (California Integrated Seismic Network), and ASU (thesis work by Lockridge, Arizona State University). The earthquake layer does not include small magnitude events (< 2.0) because of the difficulty inherent in identifying and locating such events.