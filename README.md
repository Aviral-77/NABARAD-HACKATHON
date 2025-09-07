# GreenLedger – MRV System for Paddy & Agroforestry

## Table of Contents
1. [Overview](#overview)  
2. [Technology Stack](#technology-stack)  
3. [Prototype Description](#prototype-description)  
4. [Key Features](#key-features)  
5. [Intended Users](#intended-users)  
6. [Functionality](#functionality)  
7. [Outputs](#outputs)  
   - [Example Outputs](#demo)   

---

## Overview
GreenLedger is a scalable, cost-effective **Monitoring, Reporting, and Verification (MRV) system** designed for smallholder-driven agriculture.  
It leverages **drone-based remote sensing, AI/ML models, and GIS tools** to monitor **paddy fields and agroforestry systems**.  

By detecting **tree count, type, canopy coverage, and crop health** from aerial imagery, the system generates accurate estimates of **carbon stock and sequestration**.  
This empowers **farmers, policymakers, and verifiers** to track sustainability, improve land use decisions, and unlock opportunities in **carbon credits and climate finance**.  

---

## Technology Stack
- **Remote Sensing & Drones** – High-resolution drone imagery and multispectral data for farmland and agroforestry monitoring.  
- **GIS & Geospatial Processing** – ArcGIS, QGIS, Rasterio, GeoPandas, and GeoServer for spatial analysis, mapping, and visualization.  
- **AI/ML & Computer Vision** – Vision-Language Models (VLMs), segmentation models, and zero-shot classification for crop/tree detection.  
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


### Media Samples
- 📸 **Images**:  
  - `agroforestry_tree_detection.jpg` – Example of tree detection.
- 🎥 **Videos**: 
  - `demo/mobile_app_demo.mp4` – farmer app visulaization demo.  
  - `demo/web_dashboard_demo.mp4` – Farmer/surveyor web-app usage demo.  
