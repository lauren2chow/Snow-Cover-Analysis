# Snow Cover Analysis using MODIS and AMSR-E Data

This project analyzes snow-covered areas (SCA) using MODIS and AMSR-E remote sensing data. Originally intended to be completed in ENVI as part of the **GEOG 322** course at the **UVic**, the analysis was implemented in Python for enhanced flexibility and automation. The project compares the snow cover detection abilities of MODIS and AMSR-E sensors for February and May 2011 data, calculates snow/no-snow pixel statistics, and generates visualizations for Canada’s Prairies and Rocky Mountains.

## Project Overview
- **Objective**: Compare snow-covered areas derived from MODIS (optical) and AMSR-E (passive microwave) data for February and May 2011.
- **Key Tasks**:
  - Process MODIS data using **NDSI** to identify snow-covered areas.
  - Process AMSR-E data to calculate **SWE** and derive snow cover.
  - Calculate the number of snow/no-snow pixels and their percentages.
  - Generate visualizations (maps) of snow-covered areas.
  - Compare results between MODIS and AMSR-E.
- **Outputs**:
  - Snow cover maps for February and May.
  - CSV file containing snow pixel statistics.
- **Tools Used**: `rasterio`, `numpy`, `matplotlib`, `spectral`.

![Snow Cover Map](/modis_sca_may.png)
