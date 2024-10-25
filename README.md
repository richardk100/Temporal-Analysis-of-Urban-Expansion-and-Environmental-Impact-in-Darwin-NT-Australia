# Temporal-Analysis-of-Urban-Expansion-and-Environmental-Impact-in-Darwin-NT-Australia
This project uses ArcGIS Pro and Landsat 8 imagery to analyze land use, land cover, and vegetation changes in Darwin, Northern Territory, Australia. The study focuses on the periods 2016-2019 and 2020-2023, identifying urban growth patterns and assessing environmental impacts through change detection and NDVI analysis.

## Project Overview

Darwin has experienced rapid urban expansion, leading to significant changes in land use and vegetation cover. This project applies GIS and remote sensing techniques to monitor and quantify these changes, highlighting the impact of urbanization on the region’s environment.

### Objectives
1. **Main Objective**: To detect and analyze urban growth and environmental changes in Darwin, NT, using Landsat 8 imagery and GIS methods.
2. **Specific Objectives**:
   - Calculate NDVI to assess vegetation health over time.
   - Create land use/land cover maps for multiple time periods.
   - Perform change detection analysis to identify trends in urbanization and vegetation loss.

## Methodology

### Data Collection
- **Landsat 8 Imagery**: Satellite images were obtained from the USGS Earth Explorer for the periods 2016-2019 and 2020-2023.
- **Spatial Data**: Administrative boundaries for Darwin were obtained from the Northern Territory Government Spatial Data Repository.

### Image Preprocessing
1. **Geometric Correction**: Align images with known ground control points.
2. **Atmospheric Correction**: Convert digital numbers to top-of-atmosphere reflectance.
3. **Cloud Masking**: Apply cloud masks using Landsat’s QA bands to improve data reliability.

### Analysis
- **NDVI Calculation**: Calculated NDVI using Landsat 8’s near-infrared and red bands to evaluate vegetation health across different epochs.
- **Classification**:
  - **Supervised Classification**: Classified images with the maximum likelihood algorithm using selected training data for various land cover types.
  - **Support Vector Machine (SVM)**: Refined classification with SVM for improved accuracy.
- **Land Use/Land Cover Mapping**: Generated maps showing urban, agricultural, water bodies, and other land cover types for each time period.
- **Change Detection Analysis**: Compared NDVI values and classified maps to detect significant changes between epochs, highlighting areas impacted by urban growth.

### Software
- **ArcGIS Pro**: Used for data preprocessing, classification, mapping, and visualization of results.

## Results

- **Land Use/Land Cover Maps**: Detailed LULC maps were produced, showing urban areas, water bodies, and vegetation types across time periods.
- **NDVI Analysis**: NDVI results showed a decrease in vegetation health, with urbanized areas expanding into vegetated regions.
- **Change Detection**: Significant reduction in vegetation cover was observed between 2016 and 2023, indicating the effects of unregulated urban expansion.

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/richardk100/Temporal-Analysis-of-Urban-Expansion-and-Environmental-Impact-in-Darwin-NT-Australia.git
