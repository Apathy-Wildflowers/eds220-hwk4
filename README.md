# LA Fires in False Color

## About
<img width="2464" height="1848" alt="Eaton_Fire_on_2025-1-8_(cropped)" src="https://github.com/user-attachments/assets/57f10999-ca0b-43b8-82e0-f29a68bdec59" />
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

