# SNAP-outputs-to-datacubes
Scripts to generate xarray/rioxarray/xcube datacubes (.zarr). It creates a geo-referenced xarray datacube and perform some basic operations, such as plotting multiple dates, display a time series of a lat,long, and clip raster to AOI. The following is an example of it for NDVI indices derived from Sentinel-2 imagery:

![Alt text](./VI.png?raw=true "Sentinel-2 Vegetation indices")

Similar results can be obtained for SAR imagery as shown below for the VV backscatter of the Sentinel-1 (SAR) imagery:
![Alt text](./SAR_C11.png?raw=true "Sentinel-1 SAR_C11")

SAR RGB composites can easily be generated too:
![Alt text](./SAR_RGB.png?raw=true "Sentinel-1 RGB")
