# GEOSPATIAL-DATA-VISUALIZATION
Geospatial data analysis based on railway network of "PRAGUE"
Public Transport Network Analysis

Import Libraries:
Import necessary libraries including GeoPandas, Folium, and Matplotlib.

Load GeoDataFrame:
Read the GeoJSON file containing Railway stations data using GeoPandas, storing the data in the Railway_stations variable.

Display the Matplotlib Plot:
Use plt.show() to display the Matplotlib plot showing the Railway stations

Create Folium Map:
Calculate the mean coordinates of the Railway stations and set them as the center of the Folium map.
Create a Folium map (mymap) centered around the mean coordinates with a specified zoom level.

Display the Folium Map:
Use the display function to show the Folium map.
