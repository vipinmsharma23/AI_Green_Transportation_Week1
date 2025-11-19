# AI Green Transportation 🚦🌱
AICTE Internship Project — Sustainable Transportation using AI

---

## 📌 Project Overview
This project aims to reduce carbon emissions in urban transportation by suggesting the most eco-friendly routes between two locations in Bengaluru using real road network data.

The project provides:
- Interactive shortest-route & low-emission route maps
- CO₂ emission comparison charts
- Real usable route planning for any location within Bengaluru

---

## 📆 Weekly Progress

### 🟢 Week 1 — Shortest Route Planner
- Bengaluru road network downloaded from OpenStreetMap
- Users can input any valid location in Bengaluru
- Shortest driving route calculated using NetworkX
- Generated interactive HTML map using Folium
📂 Files located inside `week1/` folder

### 🟡 Week 2 — Low-Emission Routing + CO₂ Analysis *(Current Week)*
- Added emission-weighted routing
- Calculated & compared CO₂ emissions
- Generated distance & emission bar charts
- Interactive **low emission route** map added
📂 Files will be inside `week2/` folder

---

## 🧠 Tech Stack
| Tool | Purpose |
|------|---------|
| Python | Implementation |
| OSMNX | Maps + routing |
| NetworkX | Graph calculations |
| Folium | Interactive maps |
| Matplotlib | Graphs |
| Geopy | Geocoding |

---
## ▶️ How to Run
```bash
pip install osmnx networkx folium geopy matplotlib
jupyter notebook week1_AI_Green_Transportation.ipynb

## 🟡 Week 2 – Low-Emission Route Optimization & CO₂ Analysis

### 🎯 Objective
Enhance the Week-1 routing system by integrating sustainability:
- Calculate and compare CO₂ emissions
- Add low-emission route based on road speed & congestion factors
- Provide visual interpretation of route eco-efficiency

### 🚦 Features Implemented
✔ Smart user input for any location in Bengaluru  
✔ Shortest route based on distance  
✔ Low-emission route based on:
- Road category
- Congestion levels
- Vehicle efficiency  
✔ Emission calculation using real-world logic  
✔ Two maps for route visualization:
- Blue = Shortest Route
- Green = Low-Emission Route  
✔ Comparison charts:
- Distance vs Emission  
✔ **Combined dual-route map** (most important visualization)

### 🧠 Technical Highlights
| Component | Tech Used |
|----------|-----------|
| Map Data | OSMnx + OpenStreetMap |
| Routing Model | NetworkX |
| Map Visualization | Folium |
| Charts | Matplotlib |
| Emission Modeling | Speed & road-category based factors |

### 📂 Week-2 Project Structure
week2/
├─ week2_AI_Green_Transportation.ipynb
├─ week2_shortest_route_map.png
├─ week2_low_emission_route_map.png
├─ week2_distance_comparison.png
├─ week2_emission_comparison.png
└─ week2_combined_route_image.png


### 📌 How to Run
pip install osmnx networkx folium matplotlib geopy scikit-learn
jupyter notebook week2_AI_Green_Transportation.ipynb


### 📊 Output Summary
- Low-emission route emits **less CO₂** compared to shortest route  
- Visual improvement in sustainability showcased  
- Interactive & static maps demonstrate real-world route differences

---

🔹 **Week-2 completed successfully** with sustainability-based optimization integrated into the project.
🔹 All deliverables uploaded to the `week2/` folder in this repository.
