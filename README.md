# Title - Spatiotemporal Surface Water Dynamics of the Awash River Basin, Ethiopia (2016–2025): Multi-sensor Fusion of Sentinel-1 and Sentinel-2 Data with Machine Learning Algorithms


## 📌 About

This repository contains the Python implementation of an automated surface water mapping framework built on the Google Earth Engine (GEE) for the Awash River Basin (ARB), Ethiopia .

The framework fuses Sentinel-1 SAR and Sentinel-2 MSI imagery with automatically collected training and validation samples from the JRC Global Surface Water Dataset (JRC-GSWD) and Dynamic World (DW), respectively. Four machine learning classifiers — RF, SVM, GTB, and CART — are comparatively evaluated. SVM achieved the best performance (OA = 98.6%, Kc = 0.971).
---

## Study Area

Awash River Basin (ARB), Ethiopia 
Area 114,123 km² 
Period 2016 – 2025 (Winter, Spring, Summer, Autumn)


##  Data Sources

Sentinel-1 SAR (VH, IW) 
Sentinel-2 MSI 
JRC Global Surface Water (JRC-GSWD) 
Dynamic World (DW) 
SRTM DEM 


## Classifiers Evaluated

1. Random forest (RF), 
2. Support vector machine (SVM), 
3. Gradient tree boost (GTB), and 
4. Classification and regression tree (CART)

## 📖 Citation

If you use this code, please cite:

## 👤 Authors

 Samuel Negussie Bekele, Mulugeta Musie Abdi 
 Water Resources Engineering Department, Adama Science and Technology University  
 Contact Email- saminegu6@gmail.com 
 GitHub](https://github.com/sami9029)

## 🙏 Acknowledgements

- Google Earth Engine team for the cloud computing platform
- ESA for Sentinel-1 and Sentinel-2 open-access data
- JRC for the Global Surface Water Dataset
- Google / WRI for the Dynamic World dataset
