# Snow Cover Analysis using MODIS and AMSR-E Data

This project analyzes snow-covered areas (SCA) using MODIS and AMSR-E remote sensing data. Originally intended to be completed in ENVI, the analysis was implemented in Python for enhanced flexibility and automation. The project compares snow cover products for February and May 2011, calculates snow/no-snow pixel statistics, and generates visualizations for Canada’s Prairies and Rocky Mountains.

## Project Overview
- **Objective**: Compare snow-covered areas derived from MODIS (optical) and AMSR-E (passive microwave) data for February and May 2011.
- **Key Tasks**:
  - Process MODIS and AMSR-E binary snow cover data.
  - Calculate the number of snow/no-snow pixels and their percentages.
  - Generate visualizations (maps) of snow-covered areas.
  - Compare results between MODIS and AMSR-E.
- **Outputs**:
  - Snow cover maps for February and May.
  - CSV file containing snow pixel statistics.
- **Tools Used**: Python, `rasterio`, `numpy`, `matplotlib`.
