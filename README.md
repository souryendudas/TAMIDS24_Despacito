# TAMIDS24_Despacito

# Coastal Area Submergence Analysis

This repository hosts the analysis and visualization of the submergence risks of coastal areas, focusing on Ramsar wetlands, due to rising sea levels. It leverages various datasets, including Absolute Dynamic Topography (ADT) and Global Mean Sea Level (GMSL), to analyze the intricate patterns of ocean circulation and predict the impacts of sea level rise on coastal ecosystems.

## Data Exploration

### Absolute Dynamic Topography (ADT)
ADT records from 1993 to 2023 provide detailed sea surface height measurements along the US east coast, capturing the dynamic ocean currents with a spatial resolution of 0.25 degrees. These measurements are crucial for understanding ocean circulation patterns, where higher ADT values indicate warmer currents and vice versa.

### Global Mean Sea Level (GMSL)
GMSL represents the area-weighted average of sea surface height anomalies, closely mirroring the concept of 'eustatic sea level'. It reflects the cumulative effects of ocean water mass changes, basin size adjustments, and water density variations, showcasing a linear increase in sea levels since 1992.

## Methodology

Our analysis encompasses several key methodologies:

- **Spatial and Temporal Analysis:** Utilizing the Copernicus ADT dataset, we analyze ADT changes over time and across different geographic coordinates to dissect ocean circulation patterns.
  
- **Raw Time-Series Analysis:** Leveraging data from the TOPEX, Jason, Sentinel-6 missions, and other sources, we conduct a comprehensive analysis of sea level changes from 1992 to 2022 across various latitudes and longitudes.

- **Pre-processing, Box-Plot Analysis, and Time-Series Clustering:** We apply a 30-filter window and a 3-degree polynomial Savitzky-Golay filter, followed by statistical analysis using box-plots, and clustering analysis using PCA and KMeans algorithm on the time-series data.

- **Quantitative Analysis and Geospatial Visualization:** Through the Ramsar wetlands dataset, we identify critical elevation ranges and develop a submersion score that highlights the vulnerability of wetland areas to sea level rise.

## Geospatial Visualization

Visual representations provide a clear picture of areas at high risk of submersion, emphasizing the importance of protecting these ecosystems against the impacts of climate change.

## Acknowledgments

- Recognition to all data providers, including the Copernicus dataset, NASA/JPL, and the National Tidal Centre.
- Gratitude for the inspiration and support from the scientific community in addressing climate change impacts.
