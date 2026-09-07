# 🌍 CredTitans — Land Intelligence & Verification System

[![Author](https://img.shields.io/badge/Author-Ajay%20Kumar%20Yadav-blue.svg)](https://github.com/ajaykumaryadav-collab)
[![Developer ID](https://img.shields.io/badge/Developer%20ID-AKY--2026--DEV-emerald.svg)](#)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](#)
[![React](https://img.shields.io/badge/Frontend-React%20%7C%20Vite%20%7C%20TailwindCSS-61dafb.svg)](frontend/)
[![FastAPI](https://img.shields.io/badge/Backend-FastAPI%20%7C%20Python-009688.svg)](ml-backend/)
[![NodeJS](https://img.shields.io/badge/Microservice-Node.js%20%7C%20Express-339933.svg)](roi/backend/)

An end-to-end, multimodal **AI-Powered Land Intelligence, Risk Assessment & Verification Platform**. CredTitans combines satellite imagery, OpenStreetMap GIS infrastructure radar, machine learning algorithms, and real-time news data to deliver 360° due-diligence for land parcels, investments, and agricultural/urban planning.

---

## 🌟 Key Highlights & Capabilities

### 1. 🔍 Land Verification Suite
- **Record Consistency Check**: Validates cadastral records against land registry data and survey records with cryptographic hash checks.
- **Ground Truth Analysis**: Multi-spectral satellite analysis comparing actual vegetation and land state against declared usage.
- **Interactive Polygon Mapping**: Precise parcel boundary selection with Leaflet polygon drawing, area calculation, and coordinate geometry.

### 2. 🛰️ Satellite Intelligence & NDVI Analytics
- **NDVI Health Scoring**: Computes Normalized Difference Vegetation Index in real time to assess agricultural vitality and forest cover.
- **Temporal Change Detection**: Compares historical satellite images against recent imagery to detect urbanization, deforestation, or encroachment.
- **Suitability Modeling**: Multi-criteria land scoring for agricultural, residential, commercial, or industrial applications.

### 3. 🌐 Surroundings & Infrastructure Radar
- **OpenStreetMap Overpass Engine**: Real-time POI scanning (schools, hospitals, transit, fire stations, power grids, commercial hubs).
- **Zoning Classification**: AI rule-based dominant zone breakdown (Residential, Commercial, Industrial, Agricultural) with interactive doughnut visualizations.
- **Multimodal AI Vision**: Satellite image visual interpretation and context generation.

### 4. 📈 ROI Intelligence Engine
- **Predictive Valuation**: Growth score algorithms projecting 5-year and 10-year property appreciation.
- **GenAI Investment Advisory**: Integrated Google Gemini AI for contextualized land investment guidance and risk disclosure.

### 5. 🛡️ Safety & Crime Intelligence
- **Emergency Infrastructure Density**: Proximity metrics for police stations, hospitals, and fire facilities.
- **GDELT Crime & Event Monitoring**: Ingests geo-located news and crime signals to produce normalized safety scores and risk levels.

---

## 🏗️ Architecture & Tech Stack

```
credtitans/
├── frontend/             # React 18, Vite, Tailwind CSS, Leaflet, Axios
├── ml-backend/           # FastAPI, PyTorch, OpenCV, Satellite Pipeline
├── Safety/               # FastAPI Safety & Crime News (GDELT + Overpass)
├── roi/backend/          # Node.js, Express, Gemini AI Advisor, ROI Engine
└── sorrounding check/    # Multimodal Vision & OSM Radar Microservice
```

| Component | Technology | Purpose |
|---|---|---|
| **Frontend** | React 18, Vite, TailwindCSS, Leaflet | Interactive UI, GIS map drawer, dashboards |
| **ML Backend** | Python, FastAPI, OpenCV, PyTorch | Satellite NDVI, change detection, land classification |
| **Safety Engine** | FastAPI, Overpass API, GDELT API | Emergency infrastructure & live crime intelligence |
| **ROI Service** | Node.js, Express, Google Gemini AI | Financial projections & AI investment advisory |

---

## 🚀 Quick Start

### 1. Frontend
```bash
cd frontend
npm install
npm run dev
```
App runs at `http://localhost:3000`.

### 2. Python ML & Safety Backend
```bash
pip install -r requirements.txt
cd ml-backend
python api.py
```
API runs at `http://localhost:8000` (docs at `http://localhost:8000/docs`).

### 3. ROI Intelligence Service
```bash
cd roi/backend
npm install
npm start
```
Runs at `http://localhost:5000`.

---

## 👨‍💻 Author & Developer Identification

- **Lead Developer & System Architect**: **Ajay Kumar Yadav**
- **Developer ID**: `AKY-2026-DEV`
- **Email**: `ajaykumaryadav3103@gmail.com`
- **GitHub**: [@ajaykumaryadav-collab](https://github.com/ajaykumaryadav-collab)
