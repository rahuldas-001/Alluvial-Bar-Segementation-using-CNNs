# Alluvial-Bar-Segementation-using-CNNs
This repository provides a PyTorch-based binary semantic segmentation framework designed to detect alluvial bars from satellite imagery. These geomorphological features — such as mid-channel bars, point bars, and braid bars — are crucial indicators of fluvial processes, sediment transport, and channel evolution.

🌍 Context


As a geomorphologist, alluvial bar mapping helps in:

Understanding braided river dynamics

Tracking sediment deposition and erosion patterns

Monitoring channel migration and bar formation over time

Supporting river engineering, flood hazard planning, and ecosystem monitoring

The deep learning model classifies each pixel as either:

Class 1: Alluvial bar (e.g., exposed sediment in dry conditions or vegetated barforms)

Class 0: Non-bar areas (e.g., water, vegetation, infrastructure)


📊 Use Case Example
This model has been tested on imagery with weak labels genertaed using indices such as NDWI from Google Earth Engine from Bhrahmaputra river where bar morphology changes rapidly due to monsoonal hydrology and anthropogenic interventions (e.g., dam construction, embankments).


📸 Input and Output Example


Input: 8-band satellite imagery (e.g., Sentinel-2 :(R,G,B,NIR,NDWI,NDVI)  Sentinel-1 : (SAR-VV AND VH))

Output: Binary mask of bar vs. non-bar regions


![image](https://github.com/user-attachments/assets/7b18bb45-6c90-4f66-86b8-87a29ad6ac0e)
![Screenshot 2025-05-26 113430](https://github.com/user-attachments/assets/a53b1afd-e16b-4363-a3d6-7233ed54c45d)


