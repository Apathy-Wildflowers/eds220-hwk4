# LA Fires in False Color

## About
<img width="2464" height="1848" alt="Eaton_Fire_on_2025-1-8_(cropped)" src="https://github.com/user-attachments/assets/57f10999-ca0b-43b8-82e0-f29a68bdec59" />
Image by Matt Muller
This repository creates a map of the 2025 Eaton and Pallisades Fires in LA over infrared false color imagery to show the invisible ways the fires affected the LA landscape.

### Highlights
The most important takeaways of this notebook are simple data wrangling of xarrays and raster data, using a mixture of geopandas, matplotlib, and xarray to graph data, and showing how false color imagery can let you see unknown changes in the landscape through other wavelengths.

## Repository Structure
The main python notebook that creates the maps is "hwk4-task2-false-color-SARMIENTO.ipynb", which does further analysis on the map, wrangles the raw satellite data and fire perimeters, and contains comments to understand what each line of code does. The .gitignore includes data/, so the data must be downloaded from the references section.

## Data
Data in this analysis is not contained within this repository, but was downloaded from CAL FIRE and Landsat Collection 2 Level-2.

## References
Microsoft planetary computer. (2025). Landsat Collection 2 Level-2. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

California Department of Forestry and Fire Protection's Fire and Resource Assessment Program. (2026). CAL FIRE. https://www.arcgis.com/home/item.html?id=c3c10388e3b24cec8a954ba10458039d#overview

Matt Muller, HLCO 509. (2025). USDA Forest Service. https://www.flickr.com/photos/usforestservice/54263751257/in/photolist-2qF6UJe-2qFbqND-2qFcBqA-EjLHu-2qF5jT6-2qF5p8j-2qF5yYw-2qF5qgS-2qF5p7H-aFPPJe-2qEHFkk-aFPPQH-2qF5p8z-2qF5jTM-2qFde5t-2qFcjvV-sHC6yq-2gWdyKp-nHSWHM-7iSnfe-2qFuDGx-2mcZiaU-2qFuDFR-2qFnXAQ-2qFuDJ6-2qFsvo3-2qFmQLN-2qFuDLa-2qFuDJw-2qFfbZ4-2qESg3m-2qFuDJM-2qFe5Du-2qFfgau-2qFe5De-2jxgrC2-2qFfgae-2kc3bak-9QdSkL-2jBL1Qs-WMWjm1-2qFmQUD-9phMU-2jxjL16-9Q31aA-2jxjKYC-9Q317h-72mYi-ok7VzH-2jxgr8u/
