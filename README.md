# Title: Investigating the Biodiversity Intactness Index (BII) of Phoenix from 2017 - 2020

# Purpose of Repository

Biodiversity is rapidly declining globally, and is incredibly important to healthy and robust ecosystems, and supports human society. Protecting biodiversity is a high priority for many land managers and urban planners to improve the quality of life for their constituents. Areas with higher biodiversity support more biological productivity and are healthier ecosystems (1), and human health by reducing exposures to environmental stressors and increased resources such as food and clean water, and increased mental and physical health (2). The Biodiversity Intactness Index (BII) is an estimate that incorporates both compositional similarity to a baseline healthy system and abundance of organisms. The Phoenix metropolitan area in central Arizona is rapidly expanding and building, which can cause a plethora of changes in the environment (for example, pollution, resource extraction, and land use change). All of these have the potential to impact the biodiversity of the area, and it is important to track the loss or gain of biodiversity over time to visualize these potential impacts on the environment. 

The purpose of this analysis is to compare the Biodiversity Intactness Index (BII) in the Phoenix subdivision in Arizona across time. Here, we will look at decline in biodiversity hotspots (defined as having a BII greater than or equal to 0.75) in in the Phoenix area for 2017 to 2020. Specifically, I aim to visualize and compare the loss of area with high BII (greater than or equal to 0.75) from 2017 to 2020. 

This analysis will be done using BII data from the Impact Observatory and Vizzuality (accessed through the Microsoft Planetary Computer (MPC)), and the Phoenix subdivision boundary is taken from the US census bureau. The BII data consists of rasters with a 100-meter grid resolution of terrestrial BII spanning from 2017 to 2020. We will access the BII raster files from the desired years (2017 and 2020) from the MPC, clip the raster files to the Phoenix subdivision, and calculate and visualize the difference in biodiversity intactness hotspots across the years. We will create a geographical context map using the contextilly package to orient the readers to our geographical area of interest of our Phoenix subdivision polygon. The comparison of BII across years will be done by first calculating the percentage of pixels with the high BII (using out cutoff of 0.75 as “high” BII) in both years and comparing the two. Then, we will visualize the change in these high-BII areas by subtracting the 2017 and 2020 rasters, thus, just showing the area of lost high-BII across the three years. 

Works cited
1. M. R. Marselle et al., Environment International. 150, 106420 (2021).
2. C. H. Owens, M. J. Lee, M. Grim, J. Schroeder, H. S. Young, Ecosphere. 14, e4619 (2023).

# Data Citation

Impact Observatory & Vizzuality (2022). *Biodiversity Intactness* [Data File]. Retrieved from https://planetarycomputer.microsoft.com/dataset/io-biodiversity. Access date: 12.6.2023.

United States Census Bureau, Geography Division (2022). *TIGER/Line Shapefiles County Subdivisions* [Data File]. Retrieved from https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions. Access date: 12.6.2023.


