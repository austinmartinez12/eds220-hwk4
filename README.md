# Visualizing Eaton and Palisades Fire Perimeters Using Landsat False Color Imagery

### About section:
![Palisades Fire](https://www.dailynews.com/wp-content/uploads/2025/01/LDN-L-PP-FIRE-0108-DC-20-2.jpg?w=1569)
*(Source: Daily News)*

The purpose of the notebook was to use false-color Landsat 8 imagery to visualize the extent of the January 2025 Palisades and Eaton Fire perimeters around the LA County area to highlight how it can enhance burn severity and vegetation patterns in the background image. The false-color composite used in this project was made up of SWIR, NIR, and Red bands. 

### Repository Structure:
```
.
├── hwk4-task2-false-color-Martinez.ipynb
├── README.md
└── .gitignore
```
### Author: Austin Martinez

### Data:
The data folder for this repository was put into the .gitignore for storage purposes. 

How to access the data:
- Eaton/Palisades Fire Perimeter: This data was sourced from the NIFC FIRIS program. The shapefiles can be found on this link https://hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about
- Landsat 8 Raster: The data was retrieved from the Microsoft Planetary Computer data catalogue and clipped to an area surrounding the fire perimeters. It can be found on this link: https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2 


### References:

- 1. NIFC FIRIS (2025). Palisades and Eaton Dissolved Fire Perimeters (2025, Jan. 21). https://hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about. [Accessed Nov. 20, 2025]
- 2. United States Geological Survey. Landsat Collection 2 Level-2: Microsoft Planetary Computer. (2024). https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2. [Accessed Nov. 20, 2025]