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

