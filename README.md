# Google Earth Engine Script

This script uses Google Earth Engine (GEE) to process satellite imagery and calculate various indices for a specific region.

## Script Overview

The script performs the following tasks:
1. Loads Sentinel-2 Harmonized Image Collection.
2. Filters the administrative boundaries to focus on 'Halmahera Timur' in 'Maluku Utara'.
3. Filters the Sentinel-2 images based on cloud cover percentage and date range.
4. Calculates the median image from the filtered collection.
5. Computes the following indices:
   - Normalized Difference Vegetation Index (NDVI)
   - Modified Normalized Difference Water Index (MNDWI)
   - Soil Adjusted Vegetation Index (SAVI)
   - Normalized Difference Built-up Index (NDBI)
6. Visualizes the original image and the calculated indices on the map.

