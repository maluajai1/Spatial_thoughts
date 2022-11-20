# Spatial_thoughts - project
Topic - Hurrican Harvey destruction on US state Texas using before and after Landsat data

## Hurricane – Harvey

Date of occurance- 26 August 2017- TEXAS

Landsat data : Landsat 8-9 OLI/TIRS Collection 2 Level 2

•	Path: 025,025
•	Row: 040,039


 Before 

Date : 24  May 2017

Name: Band 5,6,7 QA
LC08_L2SP_025040_20170524_20200903_02_T1 

 After

Date: 29 October 2017

Name :LC08_L2SP_025040_20170929_20200903_02_T1

## NDBI = Normal Difference Built-up Index 

NDBI = (SWIR – NIR) / (SWIR + NIR)

For Landsat 8 data, NDBI = (Band 6 – Band 5) / (Band 6 + Band 5)

The derived NDBI image was then recoded to create a binary image. The
resultant ratio was assigned a new value of 0 if the input pixel had a negative index
or 254 if its input index was larger than 0

## Normalized Difference Vegetation Index (NDVI):

NDVI = (NIR – Red) / (NIR + Red)

For Landsat 8 data, NDVI = (Band 5 – Band 4) / (Band 5 + Band 4)

In order to facilitate the subsequent processing, the derived NDVI image was
recoded with 254 for all pixels having positive indices (vegetation) and 0 for all
remaining pixels of negative indices.

## NBR =  Normalized Burn Ratio (NBR)

NBR = (Band 5 – Band 7) / (Band 5 + Band 7).


Reference:

https://www.earthdatascience.org/courses/use-data-open-source-python/multispectral-remote-sensing/landsat-in-Python/
