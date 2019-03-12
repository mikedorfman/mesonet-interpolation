# Overview of temperature interpolation

* Load input data (elevation, name, ) into pandas dataframe
* Use scipy linregress to determine a linear regression model for elevation
* Open DEM with rasterio
* Apply linear regression model to each pixel in the DEM
* Use matplotlib's imshow to save a png