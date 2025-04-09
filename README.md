# 🛰️ Remote Sensing NDVI Analysis using Google Earth Engine

This project demonstrates the use of **Google Earth Engine (GEE)** for **NDVI-based vegetation classification** in an urban park in Milan, Italy — Parco Lambro — using **Sentinel-2 satellite imagery**. The project involves time-series NDVI analysis and land cover classification using machine learning models (Random Forest and SVM).

📍 **Area of Interest:** Parco Lambro, Milan  
🗓️ **Time Period:** Spring–Summer 2022/2023  
👥 **Authors:** Özgür Gümüş & Ghazaleh Monsef Shemordeh  
📚 **Course:** Intelligent Sensing and Remote Sensing (June 2024)

---

## 🌱 Objectives

- Monitor vegetation changes using **NDVI** over time
- Classify vegetation into **trees**, **meadows**, and **bushes**
- Compare performance of **Random Forest** vs **Support Vector Machine (SVM)** classifiers
- Visualize classification accuracy and land cover area trends

---

## 🛠️ Tools & Data

- **Google Earth Engine**
- **Sentinel-2 Harmonized Imagery**
- **NDVI Calculation**: `NDVI = (B8 - B4) / (B8 + B4)`
- **Training Data**: Manually selected points for trees, meadows, and bushes
- **Classifiers**: 
  - `smileRandomForest`
  - `libsvm`

---

## 🧪 Classification Results

- Classification maps using **NDVI + ML**
- Accuracy & Kappa for RF and SVM models
- Time-series chart of **area covered by each class** (trees, meadows, bushes) throughout 2022–2023

---

## 📊 Key Visualizations

- NDVI Time Series  
- Classification Maps (RF & SVM)  
- Vegetation Class Area Chart Over Time

---

## 📄 Report

See [`report/Ozgur_Ghazaleh_Project.docx`](./report/Ozgur_Ghazaleh_Project.docx) for detailed documentation and methodology.

---

## 🧠 Code

📁 Full Earth Engine code is in [`earthengine_code/Code.js`](./earthengine_code/Code.js)  
🔗 Run the project live here:  
[🌍 Earth Engine Link](https://code.earthengine.google.com/1f8f46d4fad67e074e6f16960c7c7805?noload=true)

---

## 📌 Highlights

- Multi-temporal remote sensing analysis
- Supervised classification with explainable training zones
- Model evaluation using error matrices, accuracy, and kappa coefficient
- Practical application of GEE for urban ecological monitoring

---

Ozgur Gumus
