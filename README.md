# climate-risk-remote-sensing

🌍 Climate Risk Analysis using Remote Sensing

This repository presents a portfolio of applied projects focused on environmental monitoring and climate risk analysis using remote sensing, geospatial modeling, and machine learning techniques.

The work is centered on real-world case studies in Brazil, with an emphasis on agriculture, natural hazards, and ecosystem resilience.

------------

🎯 Objectives
	•	Analyze environmental risks using satellite data
	•	Apply machine learning and spatial modeling techniques
	•	Support climate adaptation and land management strategies
	•	Develop reproducible workflows using Google Earth Engine and Python

------------

🛰️ Tools & Technologies
	•	Google Earth Engine (GEE)
	•	Python (geospatial analysis & machine learning)
	•	QGIS
	•	Remote Sensing (Sentinel-1 SAR, Sentinel-2)

------------

📂 Projects:


🌱 Desertification Mitigation using Solar Panels

This project investigates the potential of solar panel installations to mitigate desertification processes, inspired by the Kubuqi Desert (China) model.
	•	Analysis of NDVI, EVI, and SAVI
	•	Land surface temperature variation
	•	Application to the Caatinga biome (Brazil)
	•	Identification of suitable areas for ecological restoration

📄 Google Engine Scripts: Kubuqi: https://code.earthengine.google.com/48abad85f5a134ccb60b42ef71db1d6f / Tapuio: https://code.earthengine.google.com/bdac2251ab199878c6907f283af8a77e

Full Report: https://drive.google.com/drive/folders/1BDaieS0_3p2Shr-FBeedB0AdQw1MRXEb?usp=sharing

------------

🌊 Flood Mapping using SAR and Machine Learning

This project uses Sentinel-1 SAR data combined with Random Forest classification to detect flooded areas.
	•	Radar-based flood detection
	•	Supervised classification (water, soil, vegetation)
	•	Accuracy assessment (≈0.85)
	•	Climate and precipitation analysis integration

📄 Google Engine Scripts: https://code.earthengine.google.com/d39166d8e6d0c2ca35ba4b614a16acaf

Report: SAR-Based Flood Mapping Using Machine Learning

------------

⛰️ Landslide Risk Mapping using AHP 

This project applies the Analytic Hierarchy Process (AHP) to identify landslide-prone areas.
	•	Multicriteria analysis:
	•	slope
	•	land use
	•	soil type
	•	precipitation
	•	Risk classification (low, moderate, high)
	•	Application to Juiz de Fora (Brazil)

📄 Google Engine Scripts: https://code.earthengine.google.com/46bf6c58d36f093c23b88bd8d1d30b3d

Report: Spatial Assessment of Landslide Risk Using Multi-Criteria Analysis in Juiz de Fora (MG, Brazil)

------------

 Geospatial Overlap Analysis: Protected Areas & Land Use

A Python-based spatial analysis tool designed to identify and quantify overlaps between custom geometries (such as Rural Land Registry/CAR) and Brazil's National System of Protected Areas (CNUC).

Overview
This project provides an automated pipeline to calculate environmental compliance metrics. It allows users to draw or upload areas of interest and instantly determine the spatial intersection with protected units.

 Key Features
* Precision Mapping: Automatic reprojection to metric systems (EPSG:5880) to ensure accurate area calculations in hectares.
* Interactive Dashboard: Dual-map interface using Folium for real-time geometry drawing and results visualization.
* Topology Validation: Implements geometry cleaning (buffer 0) and simplification to handle complex official datasets.
* Reporting: Automated tooltips showing Protected Area names, intersected area (ha), and percentage of total land overlap.

 Tech Stack
* Language: Python
* Spatial Stack: GeoPandas, Shapely, Pyogrio
* Visualization: Folium (Leaflet.js)

How it Works
1. Input: User draws a polygon or uploads a GeoJSON/Shapefile.
2. Process: The script performs a spatial overlay between the input and the official Protected Areas database.
3. Output: An interactive HTML report visualizing the intersection and providing key statistics for environmental due diligence.

index: https://carolezeq-analist.github.io/climate-risk-remote-sensing/
------------
📊 Additional Work
	
-	Burned area analysis using NBR - (Processing)
	
-	NDVI delta for agricultural monitoring - https://github.com/carolezeq-Analist/ndvi_seasonal_variation_italy.py
	
-	WebGIS (Folium-based visualization) - https://github.com/carolezeq-Analist/climate_gdd
    
- Map drainage network of Poços de caldas/MG (Brazil) using OSMnx. (Report: drainage.ipynb)

-------------

🚀 About Me

Environmental Management student focused on Remote Sensing, Climate Risk, and Geospatial Analysis.
	•	Strong experience with GEE, QGIS, and Python
	•	Focus on agriculture and climate applications
	•	Interested in SAR data and machine learning

------------

📬 Contact
	•	Email: carolezeq15@gmail.com
	•	GitHub: https://github.com/carolezeq
	•	Portfolio: https://carolina-geo-folio.lovable.app/
