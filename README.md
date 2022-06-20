# 3D_house Project

Description:

This is a python project for the Geospatial industry company LIDAR PLANES.
The program allows to plot in 3D a house located in Flanders with only a home address.

Installation:

To run the program, you need:

1. To download the DSM and DTM data
- [DSM](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dsm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DSM,%20raster,%201m)
- [DTM](http://www.geopunt.be/download?container=dhm-vlaanderen-ii-dtm-raster-1m&title=Digitaal%20Hoogtemodel%20Vlaanderen%20II,%20DTM,%20raster,%201m)

2. To install following libraries:
- requests 
- json
- shapely
- rasterio
- matplotlib

Difficulties:

1. I had difficulties importing Rasterio and GDAl packages in jupyter notebook. So I switched to Google collab.
2. There was an error while clipping the Tiff files(RasterioI/O error), for which I couldn't find the solution.


   



