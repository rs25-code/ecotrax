# Species Distribution Modeling using Google Earth Engine and iOS Mobile App using Swift


This project uses Species Distribution Modeling techniques to predict the impact of future climate change on the habitat suitability and population distribution of the California Condor (Gymogyps californianus). 
An iOS app was also developed using Swift to display historical and predicted population distribution areas.


- Historical Species Occurrence data - Global Biodiversity Information Facility (GBIF)
- Historical Climate Data
  - Bioclimatic variables - Worldclim Bioclim (https://www.worldclim.org/data/worldclim21.html)
  - Terrain - NASA SRTM (https://developers.google.com/earth-engine/datasets/catalog/USGS_SRTMGL1_003)
  - Global Forest Cover Change - NASA Landsat Vegetation Continuous Fields (VCF) (https://developers.google.com/earth-engine/datasets/catalog/NASA_MEASURES_GFCC_TC_v3)
  - Normalized Difference Vegetation Index (NDVI) - MODIS (MODIS/006/MOD13Q1)
  - Normalized Difference Moisture Index - Landsat 9 NDMI (LANDSAT/LC09/C02/T1_L2)
  - Wildfire - MODIS Burned Area data product (MODIS/006/MCD64A1)
- Furure Climate data
  - CMIP6 SSP 370 pathway future bioclimatic variables in 20-year blocks (https://www.worldclim.org/data/cmip6/cmip6_clim10m.html)
