# 3D View of Mumbai

## 📌 Project Overview
This project visualizes **Mumbai's buildings in 3D** using **QGIS** and the **Qgis2threejs** plugin. The interactive map allows users to explore Mumbai’s cityscape with zoom, pan, and rotation controls.

## 🌍 Website Link (Deployment Link)
[3D View of Mumbai](https://3dviewofmumbai.vercel.app/)

## 🛠️ Requirements
- **QGIS (Latest Version)** – Download from [QGIS Official Site](https://qgis.org/)
- **Required Plugins:**
  - [Qgis2threejs](https://plugins.qgis.org/plugins/Qgis2threejs/)

## 📂 Datasets Used
| Data Type      | Source | Description |
|---------------|--------|-------------|
| **Digital Elevation Model (DEM)** | [USGS Earth Explorer](https://earthexplorer.usgs.gov/) | Provides terrain elevation data |
| **Mumbai Building Footprints** | [Geofabrik OSM](http://download.geofabrik.de/asia/india.html) or **QuickOSM Plugin** | Contains building footprints |
| **Satellite Imagery** | [Sentinel-2](https://scihub.copernicus.eu/) or [Google Maps Tile Service] | Used as a basemap |
| **Buildings Elevation** | [ONEGEO](https://map.onegeo.co/) | Used for height |

## 🚀 Step-by-Step Guide

### 1️⃣ Data Collection & Preparation
1. **Download DEM** for Mumbai from USGS Earth Explorer.
2. **Download Mumbai Building Footprints** from Geofabrik or QuickOSM plugin.
3. **Download Satellite Imagery** for Mumbai from Sentinel-2 or Google Maps.
3. **Download Buildings Elevation** for Mumbai from ONEGEO.

### 4️⃣ Export 3D Interactive Map
1. Open **Qgis2threejs Plugin** via **Web > Qgis2threejs**.
2. Select **DEM, building footprints, and imagery** for export.
3. Configure settings (camera, lighting, resolution).
4. Click **Run** to generate the interactive **HTML file**.

### 5️⃣ Test & Share the Map
- Open the exported **HTML file** in a web browser.
- Host on a web server for online access.

## 📌 Project Output
- An **interactive 3D web map** showcasing **Mumbai's buildings**.
- Viewable in any modern web browser.

## 📜 License
This project is for educational purposes. Data sources follow their respective usage licenses.

---
👨‍💻 **Created with QGIS & Open Data** 🌍
