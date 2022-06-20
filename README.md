# 3D_house Project

Description:

This is a python project for the Geospatial industry company LIDAR PLANES.
The program allows to plot in 3D a house located in Flanders with only a home address.

Objectives:

- to be able to search and implement new libraries
- to be able to read and use the [shapefile](https://en.wikipedia.org/wiki/Shapefile) format
- to be able to read and use geoTIFFs
- to be able to render a 3D plot
- to be able to present a final product

Installation:

To run the program, you need:

1. To download the DSM and DTM data
- [DSM](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dsm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DSM,%20raster,%201m)
- [DTM](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dtm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DTM,%20raster,%201m)

2. To install the following libraries:
- requests 
- json
- shapely
- rasterio
- matplotlib

Difficulties:

1. I had difficulties importing Rasterio and GDAl packages in jupyter notebook. So I switched to the Google collab.
2. There was an error while clipping the Tiff files(RasterioI/O error), for which I couldn't find the solution.

Progress:

- Managed to find polygon of the given address and desired tiff files for that address.
- Couldn't able to finished the code for complete project.
   



