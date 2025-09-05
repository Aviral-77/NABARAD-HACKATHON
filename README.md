# AgriVeritas – MRV System for Paddy & Agroforestry

## Overview
AgriVeritas is a scalable, cost-effective **Monitoring, Reporting, and Verification (MRV) system** designed for smallholder-driven agriculture.  
It leverages **drone-based remote sensing, AI/ML models, and GIS tools** to monitor **paddy fields and agroforestry systems**.  

By detecting **tree count, type, canopy coverage, and crop health** from aerial imagery, the system generates accurate estimates of **carbon stock and sequestration**.  
This empowers **farmers, policymakers, and verifiers** to track sustainability, improve land use decisions, and unlock opportunities in **carbon credits and climate finance**.  

---

## Technology Stack
- **Remote Sensing & Drones** – High-resolution drone imagery and multispectral data for farmland and agroforestry monitoring.  
- **GIS & Geospatial Processing** – ArcGIS, QGIS, Rasterio, GeoPandas, and GeoServer for spatial analysis, mapping, and visualization.  
- **AI/ML & Computer Vision** – Vision-Language Models (VLMs), YOLO for object detection, SAMGeo for segmentation, and zero-shot classification for crop/tree detection.  
- **Height & Biomass Estimation** – DEMs and CHMs to estimate tree height and biomass.  
- **Mobile Application** – Kotlin-based Android app for field-level data collection, ground-truthing, and farmer access.  
- **Data Management & APIs** – PostgreSQL/PostGIS for spatial data storage with REST APIs.  
- **Visualization & Dashboard** – Web GIS dashboard for carbon stock tracking, paddy monitoring, and agroforestry insights.  

---

## Prototype Description
The prototype integrates **processed raster and shapefile data** into two interfaces:  
- **Android app** – Primary field tool for farmers and surveyors with farm- and village-level insights, plus ground-truth data collection.  
- **Web dashboard** – Centralized platform for stakeholders to visualize geospatial layers such as tree count, crop type, canopy height, and land cover.  

Together, these enable **transparent and verifiable monitoring** of paddy and agroforestry systems, supporting **carbon stock estimation, yield assessment, and MRV reporting**.  
The solution is designed to be **low-cost, accessible, and scalable across diverse agro-climatic zones**.  

---

## Key Features
- **Geospatial Data Integration** – Raster and shapefile layers for land cover, paddy fields, and agroforestry trees.  
- **Paddy Monitoring** – Seasonal tracking, yield estimation, and methane emission indicators for climate-smart rice cultivation.  
- **Agroforestry Insights** – Tree survival verification, canopy height, and carbon sequestration estimates.  
- **Mobile Application** – Android app for offline/low-connectivity farmer and surveyor use.  
- **Web Dashboard** – Aggregated analysis for NABARD, policymakers, and researchers.  
- **MRV Functionality** – End-to-end support for **Monitoring, Reporting, and Verification** workflows.  
- **Scalable & Smallholder-Friendly** – Deployable across different agro-climatic zones at low cost.  

---

## Intended Users
- **Farmers & Surveyors** – For field-level monitoring, data entry, and feedback.  
- **NABARD & Policymakers** – For program evaluation, subsidy targeting, and MRV compliance.  
- **Researchers & Verifiers** – For dataset validation, carbon modeling, and third-party audits.  

---

## Functionality
1. Drone and satellite data are collected and processed into **raster and shapefile outputs**.  
2. Data is integrated into the **Android app** (field-level visualization & ground-truthing).  
3. Aggregated data is displayed in the **web dashboard** for policymakers and verifiers.  
4. Supports **carbon estimation, methane tracking in paddy systems, and agroforestry verification**.  
5. Creates a **transparent, verifiable, and scalable MRV ecosystem** for smallholder agriculture.  

---

## Outputs
The prototype generates outputs in the form of **maps, analysis layers, and field insights**.  
These can be exported as **images, videos, and interactive dashboards** for stakeholders.  

### Example Outputs
- **Raster-based maps** of paddy fields and agroforestry plots.  
- **Shapefile visualizations** showing tree locations, canopy coverage, and survival rates.  
- **Carbon stock estimation charts** from processed DEM/CHM data.  
- **Mobile screenshots** of farm-level insights for farmers and surveyors.  
- **Web dashboard visuals** displaying aggregated village-level or project-level MRV data.  

### Media Samples
- 📸 **Images**:  
  - `outputs/tree_detection_map.png` – Example of YOLO + SAMGeo-based tree detection.  
  - `outputs/paddy_classification.png` – Paddy crop type and yield classification.  
  - `outputs/dashboard_view.png` – MRV dashboard screenshot.  

- 🎥 **Videos**:  
  - `outputs/farm_walkthrough.mp4` – Drone-to-dashboard workflow demo.  
  - `outputs/android_app_demo.mp4` – Farmer app usage demonstration.  

---

## Unique or Impactful Aspects
- **Farmer-Centric MRV** – Empowers farmers with direct participation via mobile app.  
- **Dual Focus** – Simultaneously monitors **paddy methane emissions** and **agroforestry carbon sequestration**.  
- **Hybrid Data Fusion** – Combines drone, satellite, and field inputs into verifiable geospatial datasets.  
- **Cost-Effective & Scalable** – Uses open-source geospatial tools and lightweight mobile apps to reduce MRV costs.  
- **Aligned with NABARD’s Mission** – Directly supports rural livelihoods, sustainable farming, and inclusive climate action.  

---

## Key Innovation / Differentiator
- **Farmer-first approach** – Shifts MRV from top-down to participatory and field-driven.  
- **Integrated Monitoring** – Unifies paddy and agroforestry into one MRV solution.  
- **Data Fusion at Scale** – Merges drone imagery, satellite datasets, and ground data for high accuracy.  
- **Affordable Climate MRV** – Tailored for smallholders in resource-constrained environments.  

---

## License
This project is developed for the **NABARD Hackathon 2025**.  
Future releases may be published under an **open-source license** for wider adoption.  
