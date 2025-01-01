# Flood Inventory Creation Using Sentinel-1 and Sentinel-2 Data in Google Earth Engine

This repository is code I used for creating flood inventory for 2018 and 2019 flood events in Kochi region of Kerala. Also I did field verification for the results and I got 72% accuracy. 

The project focuses on the development of flood inventories for the Kochi Metropolitan Region for the years 2018 and 2019. It utilizes Sentinel-1 Synthetic Aperture Radar (SAR) data for water detection during flood events and Sentinel-2 optical data for identifying permanent water bodies using NDWI. The project implements a combination of Lee filtering for speckle reduction, thresholding techniques, and temporal change detection to extract flooded areas.

## Key Features

- **Flood Mapping**: 
  Identification of flood-affected regions using multi-temporal Sentinel-1 SAR data (VV and VH polarizations) and Sentinel-2 imagery.

- **Temporal Analysis**: 
  Comparison of flood and pre-flood data to isolate significant water extent changes during the flood events.

- **Topographical Constraints**: 
  Incorporation of SRTM-based slope data to mask steep areas unlikely to flood.

- **Thresholding**: 
  Application of Otsu thresholding to derive permanent water bodies and refine flood maps.

- **Automated Workflow**: 
  A streamlined process implemented in Google Earth Engine to generate flood inventories for multiple years.

- **Export Options**: 
  Final flood maps are exported in high resolution for further analysis and integration into urban flood modeling frameworks.

## Technology Stack
- **Google Earth Engine**: For cloud-based geospatial processing.
- **Sentinel-1 SAR Data**: For detecting water bodies during and after flood events.
- **Sentinel-2 Optical Data**: For deriving NDWI and identifying permanent water regions.
- **SRTM DEM Data**: For incorporating topographical constraints.

This workflow is a critical step in creating flood inventories that can support advanced flood modeling and mitigation strategies in urban areas.
