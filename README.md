# mesonet-interpolation
Taking weather readings from various mountainous weather stations and generating a 2-d raster of interpolated surface readings.

## Inputs
* JSON containing:
  * Site identifier
  * Site value
  * Site elevation
  * Site latitude and longitude
* Digital Elevation Model data

## Outputs
* Plot of readings (x-axis) vs elevation (y-axis) with a vertical line at freezing (png)
* Raster output (png)
* Raster colorbar legend (png)
* Temperature x/y/z gradient information (json)
