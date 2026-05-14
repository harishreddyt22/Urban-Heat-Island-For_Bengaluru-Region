# Urban Heat Island Analysis for Bengaluru Region

## Overview
This project focuses on analyzing the **Urban Heat Island (UHI)** effect in the Bengaluru region using satellite imagery, geospatial analysis, and machine learning techniques. The study identifies temperature variations across urban and surrounding regions by processing Landsat imagery and generating Land Surface Temperature (LST) maps.

The project leverages **Google Earth Engine (GEE)** for satellite data collection and preprocessing, **ArcMap** for spatial analysis and visualization, and **Random Forest Regression** for modeling and predicting urban heat patterns.

---

## Objectives
- Analyze the Urban Heat Island effect in Bengaluru.
- Extract and preprocess Landsat satellite imagery.
- Calculate Land Surface Temperature (LST).
- Identify urban hotspots and cooler regions.
- Apply machine learning techniques for accurate temperature prediction.
- Visualize spatial heat distribution using geospatial tools.

---

## Dataset
The satellite imagery data used in this project was collected from:

- **Google Earth Engine Code Editor**
- **Landsat Satellite Imagery**

### Data Includes
- Thermal Infrared Bands
- Land Surface Temperature (LST)
- Vegetation and land cover information
- Urban and non-urban spatial regions

---

## Tools & Technologies

| Tool / Technology | Purpose |
|-------------------|---------|
| Google Earth Engine (GEE) | Satellite data collection and preprocessing |
| ArcMap | Spatial analysis and visualization |
| Landsat Imagery | Remote sensing data source |
| Random Forest Regression | Temperature prediction and modeling |
| JavaScript (GEE) | Data extraction and image processing |
| GIS Techniques | Mapping and geospatial analysis |

---

## Methodology

### 1. Data Collection
- Downloaded Landsat imagery using Google Earth Engine.
- Selected Bengaluru region boundary for analysis.
- Extracted thermal and spectral bands required for LST calculation.

### 2. Data Preprocessing
- Cloud masking and image correction.
- Region clipping for Bengaluru urban area.
- Generation of composite satellite images.

### 3. Land Surface Temperature (LST) Calculation
- Converted thermal band values into temperature measurements.
- Generated LST raster layers for the study region.

### 4. Machine Learning Model
- Applied **Random Forest Regression** to analyze temperature patterns.
- Used environmental and land cover parameters as input features.
- Improved prediction accuracy for urban heat intensity mapping.

### 5. Visualization & Mapping
- Created Urban Heat Island maps using ArcMap.
- Represented heat intensity using color gradients (CMYK representation).
- Identified hotspots and cooler zones across Bengaluru.

---

## Project Workflow

```text
Landsat Imagery
        ↓
Google Earth Engine Processing
        ↓
Preprocessing & Feature Extraction
        ↓
Land Surface Temperature Calculation
        ↓
Random Forest Regression Modeling
        ↓
ArcMap Visualization & UHI Mapping
