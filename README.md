# Raspberry Pi Handheld NDVI Prototype

## NDVI ##

NDVI or Normalized Difference Vegetation Index is a remote sensing method that uses the reflectance of light in the visible and near-infrared (NIR) wavelengths to determine the amount and health of vegetation in an area. NDVI is widely used in agriculture, forestry, and ecology to monitor the growth and health of vegetation and to identify areas of stress or damage. 

Normalized Difference Vegetation Index is an indicator of a plant’s health entirely based on how the cell structures reflect the different light waves in visible and near-infrared bands.

It aids in detecting and quantifying the presence of live green vegetation based on how objects interact with light. To understand the plant’s health condition, one needs to compare the absorption and reflection values of red and NIR (near-infrared) light.

## Prototype Functioning ##

The optical data is captured by RPi NoIr Camera and processed by the onboard Raspberry Pi 3B using NDVI algorithm which is then color mapped to allow easy interpration for human eyes. This map is then displayed on a Touchscreen LCD navigated via a simple UI to collect and process data on spot. 

The entire assembly with onboard power supply is conveniently packed inside a 3D printed case with staus LED indicator and buzzer

