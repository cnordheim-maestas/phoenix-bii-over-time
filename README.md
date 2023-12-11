# Title: Investigating the Biodiversity Intactness Index (BII) of Phoenix from 2017 - 2020

# Purpose of Repository

Biodiversity is incredibly important to healthy environments, and supports human well-being and society, and needs to be protected. Thus, it is vital to track changes in biodiversity to inform land management and conservation efforts. The Phoenix metropolitan area is rapidly expanding and building, and it is important to track biodiversity as these changes occur through time. Here, we will look at declining biodiversity hotspots in in the Phoenix area for 2017 to 2020. The purpose of this analysis is to compare the Biodiversity Intactness Index (BII) in the Phoenix subdivision in Arizona across time. Specifically, I aim to visualize and compare the loss of area with high BII (greater than or equal to 0.75) from 2017 to 2020. 

This analysis will be done using BII data from the Impact Observatory and Vizzuality (accessed through the Microsoft Planetary Computer (MPC)), and the Phoenix subdivision boundary is taken from the US census bureau. The BII data consists of rasters with a 100-meter grid resolution of terrestrial BII spanning from 2017 to 2020. We will access the BII raster files from the desired years (2017 and 2020) from the MPC, clip the raster files to the Phoenix subdivision, and calculate and visualize the difference in biodiversity intactness hotspots across the years. We will create a geographical context map using the contextilly package to orient the readers to our geographical area of interest of our Phoenix subdivision polygon. The comparison of BII across years will be done by first calculating the percentage of pixels with the high BII (using out cutoff of 0.75 as “high” BII) in both years and comparing the two. Then, we will visualize the change in these high-BII areas by subtracting the 2017 and 2020 rasters, thus, just showing the area of lost high-BII across the three years. 

# Data Citation

Impact Observatory & Vizzuality (2022). *Biodiversity Intactness* [Data File]. Retrieved from https://planetarycomputer.microsoft.com/dataset/io-biodiversity. Access date: 12.6.2023.

United States Census Bureau, Geography Division (2022). *TIGER/Line Shapefiles County Subdivisions* [Data File]. Retrieved from https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions. Access date: 12.6.2023.


