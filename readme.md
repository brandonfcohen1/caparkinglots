# Calculate the area of surface parking owned by the State of California

I found a database of state real estate holdings [here](https://www.dgsapps.dgs.ca.gov/RESD/SPI-Web/wscripts/spi.asp?action=Main), which had [this REST Service](https://services8.arcgis.com/a4GMqC2tQHvYiVtK/ArcGIS/rest/services/SPIPublicMapViewer/FeatureServer/2) of [points](carealestate.geojson).

I downloaded parking for all of CA from [OSM using Overpass](osm_parking.geojson.zip), and did a Spatial Join to produce [state_parking_lots.geojson](state_parking_lots.geojson).

The total area of these shapes (exported as [output_features.csv](output_features.csv)) is 2,763,416.193 m2, or 682.9 acres.
