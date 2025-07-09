# 🏞️ Green Welfare Viewer for Chinese Cities (Existing Situation vs. Planned Situation)


> 🔗 Online Viewer:  
> [https://pku-aaronyang.github.io/Green_welfare/]

## 📌 Project Overview |

This project provides an interactive visual interface to compare park exposure equality and equity under the existing and planned situation urban park layouts across 355 Chinese cities.  
It supports province/city selection and image zoom/pan operations, offering a detailed visual representation of spatial justice in urban park planning.

## 🧭 Features | 

- 🌍 Covers all 31 provinces and 355 cities in China  
- 🏙️ Displays 6 comparative figures per city  
- 🔎 Supports zooming and panning for detailed inspection  
- 🧩 Dynamic dropdown selection for province & city  
- 🌐 Fully deployable via GitHub Pages  

## 📁 Folder Structure | 

```plaintext
├── index.html                   #  HTML 
├── CityData_structure.json      # Province-city structure index (for drop-down boxes)
├── UIData/
│   └── figE.png                 # Static reference image
├── CityData/
│   └── <Province>/
│       └── <City>/
│           ├── figA.png        # Existing Park Layout
│           ├── figB.png        # Planned Park Layout
│           ├── figC.png        # Equality Change
│           ├── figD.png        # Equity Change
│           ├── figX.png        # Province Reference Map
│           └── figY.png        # City Reference Map

🚀 Deployment Guide | 
This project uses GitHub Pages for static hosting;
All images are committed as normal Git files;


🔍 Usage | 
After opening the webpage, select the province and city;
Browse 6 city-related images (including existing situation, planned situation, changes and reference images);
Support zooming and dragging to browse details through the mouse wheel.


📮 Contact | 
Maintainer: Zhiwei Yang
Email: yangzw9615@163.com

This project is part of a broader research on urban green welfare, spatial inequality/inequity, and planning justice in China.
