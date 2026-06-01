# 🌾 AgroVision

### AI-Powered Satellite Crop Monitoring & Geospatial Intelligence Platform

AgroVision is an advanced geospatial agriculture intelligence dashboard that combines satellite remote sensing, GIS visualization, environmental analytics, and AI-assisted crop monitoring to analyze agricultural land directly from space.

The platform uses live Sentinel-2 satellite imagery and environmental intelligence to monitor vegetation health, detect crop stress, analyze environmental conditions, and generate agricultural insights in real time.

---

# 🚀 Features

* 🛰️ Live Sentinel-2 Satellite Monitoring
* 🌱 NDVI Crop Health Analysis
* 🗺️ Interactive GIS Polygon Selection
* 📈 Time-Series Vegetation Monitoring
* 🌧️ Weather Intelligence Integration
* 🚨 AI-Based Health Alerts
* 💧 Soil Moisture Analysis
* 🌊 Flood Detection Analytics
* 🤖 AI Crop Advisory Engine
* 📊 Real-Time Dashboard Visualization
* 🌍 Multi-Layer Satellite Mapping

---

# 🖥️ Dashboard Preview


## 🌍 Main Dashboard



![Dashboard](https://github.com/Swethancyber/AgroVision/blob/main/image/agrovision-dashboard.png)

---

## 🤖 AI Prediction Engine


![AI Prediction](https://github.com/Swethancyber/AgroVision/blob/main/image/ai-prediction-engine.png)

---

## 🌱 Crop Health Analysis



![Crop Health](https://github.com/Swethancyber/AgroVision/blob/main/image/crop-health-analysis.png)

---

## 🌦️ Environmental Analytics



![Environmental Analytics](https://github.com/Swethancyber/AgroVision/blob/main/image/environmental-analytics.png)

---

## 🚨 Health Alerts



![Health Alerts](https://github.com/Swethancyber/AgroVision/blob/main/image/health-alerts.png)

---

## 📈 Vegetation Timeline



![Vegetation Timeline](https://github.com/Swethancyber/AgroVision/blob/main/image/vegetation-timeline.png)

---

# 🛰️ Technologies Used

| Domain             | Technology                |
| ------------------ | ------------------------- |
| Frontend           | Streamlit                 |
| GIS Visualization  | Folium                    |
| Satellite APIs     | Sentinel Hub              |
| Data Processing    | NumPy                     |
| Data Visualization | Plotly / Matplotlib       |
| Weather APIs       | Open-Meteo                |
| Geospatial APIs    | OpenStreetMap             |
| Future AI Stack    | TensorFlow / Scikit-learn |

---

# 🌍 Project Goal

The primary objective of AgroVision is to transform raw Earth observation data into actionable agricultural intelligence using geospatial analytics and remote sensing technologies.

The platform enables:

* crop health monitoring
* vegetation stress detection
* drought analysis
* environmental intelligence
* smart farming visualization
* AI-assisted agricultural recommendations

without requiring physical field inspection.

---

# 🛰️ Satellite Data Source

The platform uses live Earth observation data from:

* European Space Agency (ESA) Sentinel-2
* Sentinel Hub APIs

### Spectral Bands Used

| Band | Purpose                    |
| ---- | -------------------------- |
| B02  | Blue                       |
| B03  | Green                      |
| B04  | Red                        |
| B08  | Near Infrared (NIR)        |
| B11  | Shortwave Infrared (SWIR)  |
| SCL  | Scene Classification Layer |

---

# 🔬 Scientific Methodology

## NDVI Formula

NDVI = (NIR - Red) / (NIR + Red)

Healthy vegetation strongly reflects Near Infrared wavelengths while absorbing red light because of chlorophyll activity.

### NDVI Interpretation

| NDVI Range | Interpretation             |
| ---------- | -------------------------- |
| 0.6 – 1.0  | Healthy vegetation         |
| 0.3 – 0.6  | Moderate vegetation        |
| 0.1 – 0.3  | Weak vegetation            |
| < 0.1      | Bare soil / unhealthy crop |

---

# ☁️ Cloud Masking Engine

Cloud-contaminated pixels are automatically removed using Sentinel-2 Scene Classification Layer (SCL) masking to improve vegetation analysis accuracy.

The masking engine filters:

* cloud pixels
* cloud shadows
* cirrus contamination
* invalid pixels

---

# 🌱 Spectral Indexes Used

## NDVI — Vegetation Health

NDVI = (NIR - Red) / (NIR + Red)

Used for:

* crop health monitoring
* chlorophyll analysis
* vegetation intensity

---

## NDMI — Moisture Analysis

NDMI = (NIR - SWIR) / (NIR + SWIR)

Used for:

* drought analysis
* water stress detection
* soil moisture estimation

---

## NDWI — Water Detection

NDWI = (Green - NIR) / (Green + NIR)

Used for:

* flood detection
* water body analysis
* irrigation monitoring

---

# 🧠 AI Prediction Engine

Current version includes:

* rule-assisted crop stress analysis
* environmental recommendation engine
* simulated predictive analytics pipeline

### Planned Future Upgrades

* CNN Crop Classification
* Disease Detection AI
* Yield Prediction Models
* SAR Radar Soil Moisture Analysis
* Drone-Based Crop Monitoring
* Tamil Voice AI Farming Assistant

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/Swethancyber/AgroVision.git
cd AgroVision
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Application

```bash
streamlit run app.py
```

---

# 📦 Required Libraries

```bash
pip install streamlit sentinelhub numpy matplotlib folium streamlit-folium plotly requests
```

---

# 🚀 Future Enhancements

* Real CNN Crop Classification
* Disease Detection AI
* Real-Time Satellite Monitoring
* Climate Risk Prediction
* Multi-Farm Monitoring
* Voice-Based Tamil AI Assistant
* Drone + Satellite Hybrid Monitoring
* Predictive Agricultural Intelligence

---

# 🌍 Real-World Applications

* Precision Agriculture
* Smart Farming Systems
* Crop Health Monitoring
* Environmental Intelligence
* Climate Analytics
* Agricultural Decision Support
* Water Stress Analysis
* Disaster & Flood Monitoring

---

# ⚠️ Disclaimer

This project is intended for educational, research, and innovation purposes.

---

# 👨‍💻 Author

swethan

Geospatial AI | Remote Sensing | Precision Agriculture | Environmental Intelligence

GitHub:
https://github.com/Swethancyber
