# Project 4 – Clustering U.S. Air Pollution Profiles

This notebook explores 24 years of EPA Air Quality Index (AQI) data and uncovers six distinct pollution profiles across 181 U.S. city–county pairs. By clustering mean AQI values for ozone, carbon monoxide, sulfur dioxide, and nitrogen dioxide, 
I outline how air-quality challenges differ by region: from car-centric metros, sulfur-heavy industrial hubs, and ultra-clean baseline areas.

## Highlights

- **Data prep:** 663,000+ daily AQI readings (2000–2023) cleaned and aggregated to city/county/state level.
  
- **Model selection:** Compared KMeans vs. Ward agglomerative using WCSS, Silhouette, Davies–Bouldin, and Calinski–Harabasz; KMeans with *k = 6* provided the best balance of compactness and separation.
  
- **Cluster profiles:**
  - Industrial mix (high SO₂ + sunlight)
  - Clean baseline group
  - Traffic hotspots (CO/NO₂ heavy)
  - Urban/suburban blend
  - Sulfur-rich industrial zones
  - Sunbelt ozone hotspots
    
- **Validation:** Mapped the six clusters onto county population data.
  - Findings supported high population density in the traffic cluster
  - Refinery-heavy counties dominate the sulfur-rich cohort.

## Folder Structure
- This repository contains the ZIP file of the most current version. 

- ZIP file includes: 
  - Output folder to store visuals
  - Both CSV files
  - Most recent notebook
