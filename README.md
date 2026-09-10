# NDVI Time-Series Analysis with Google Earth Engine

A remote-sensing project that examines vegetation patterns in **Parco Lambro, Milan** using Sentinel-2 imagery, NDVI time series, and supervised land-cover classification in Google Earth Engine.

## Objectives

- Measure vegetation change across the 2022–2023 study period
- Classify trees, meadows, and bushes from satellite-derived features
- Compare Random Forest and Support Vector Machine classifiers
- Track the estimated area of each vegetation class over time
- Evaluate classification quality with confusion matrices, accuracy, and Cohen’s kappa

## Data and Methods

- **Area of interest:** Parco Lambro, Milan, Italy
- **Imagery:** Sentinel-2 harmonized surface reflectance
- **Vegetation index:** `NDVI = (B8 - B4) / (B8 + B4)`
- **Training data:** Manually labeled reference points
- **Classifiers:** `smileRandomForest` and `libsvm`
- **Platform:** Google Earth Engine

## Repository Contents

| File | Description |
|---|---|
| [`Code.txt`](./Code.txt) | Google Earth Engine JavaScript implementation |
| [`Ozgur_Project.pdf`](./Ozgur_Project.pdf) | Final project report |
| [`Ozgur_Ghazaleh_Project.docx`](./Ozgur_Ghazaleh_Project.docx) | Editable report document |

The analysis can also be opened in [Google Earth Engine](https://code.earthengine.google.com/1f8f46d4fad67e074e6f16960c7c7805?noload=true).

## Outputs

- Seasonal NDVI time-series charts
- Random Forest and SVM classification maps
- Accuracy and kappa comparisons
- Vegetation-class area trends

## Academic Context

**Authors:** Özgür Gümüş and Ghazaleh Monsef Shemordeh  
**Course:** Intelligent Sensing and Remote Sensing  
**Institution:** University of Milano-Bicocca  
**Year:** 2024

