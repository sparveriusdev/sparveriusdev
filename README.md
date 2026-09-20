<div align="center">

# 👋 David Vasquez
### Geospatial Developer | Drone Pilot | AI Engineer

[![GitHub](https://img.shields.io/badge/GitHub-sparverius-181717?style=flat&logo=github)](https://github.com/sparverius)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/davidvasquez)
[![YouTube](https://img.shields.io/badge/YouTube-SkyMapStories-FF0000?style=flat&logo=youtube)](https://youtube.com/@skymapstories)
[![Website](https://img.shields.io/badge/Web-skymapstories.com-4A90E2?style=flat&logo=google-chrome)](https://skymapstories.com)

</div>

---

## 🚀 About Me

Geospatial developer and aerial photographer specialized in **photogrammetry**, **cadastral systems**, and **artificial intelligence for land surveying**. With a strong background in GIS, drone technology, and Python development, I create innovative solutions that bridge the gap between technology and real-world geospatial challenges.

**Co-creator of [TipologIA](https://github.com/SESMAPS/Tipologia)** - Colombia's first AI-powered cadastral recognition system, fully compliant with the **LADM-COL** standard.

Currently building **SkyMapStories** - capturing stunning aerial perspectives and providing professional topographic services with drones.

---

## 💼 Professional Expertise

### 🗺️ **Geospatial Development**
- **GIS & Cartography**: QGIS, ArcGIS, PostGIS, Spatial Analysis
- **Cadastral Systems**: LADM-COL model implementation
- **Topographic Surveying**: Ground control, precision mapping, volumetric calculations
- **Photogrammetry**: Pix4D, Agisoft Metashape, WebODM, 3D modeling

### 🤖 **Artificial Intelligence & Machine Learning**
- **Computer Vision**: Object detection, image classification, semantic segmentation
- **Deep Learning**: TensorFlow, PyTorch, YOLO, U-Net architectures
- **Cadastral AI**: Property recognition and classification (TipologIA)
- **Geospatial AI**: Land use classification, change detection

### 🚁 **Drone Technology**
- **UAV Operations**: DJI Mini 3, commercial drone piloting
- **Aerial Photogrammetry**: Orthomosaics, DEMs, DSMs, point clouds
- **Mission Planning**: Flight automation, GCP placement, optimal coverage
- **Data Processing**: Structure from Motion (SfM), LiDAR processing

### 💻 **Software Development**
- **Languages**: Python, SQL, JavaScript, Bash
- **Frameworks**: Flet, Django, FastAPI, Flask
- **Databases**: PostgreSQL/PostGIS, SQLite, MongoDB
- **DevOps**: Git, Docker, CI/CD (GitHub Actions), Nuitka

---

## 🏆 Featured Projects

---
### 📡 **Alertas Sísmicas Colombia** - Meshtastic Earthquake & Volcano Alert System
  <img src="https://img.shields.io/badge/Platform-Windows%20|%20Linux%20|%20Android-lightgrey?style=flat" />

  Real-time seismic/volcanic alert notifier for Colombia, delivered over your own Meshtastic LoRa mesh — no cell signal or internet required:
  - 🛰️  Live polling of Colombia's official SGC feed, with automatic failover to USGS if it goes down
  - 📻 Meshtastic LoRa notifications with tap-to-build message templates (magnitude, location, agency, etc.)
  - 🗺️  Interactive live map color-coded by the same alert severity scale as the SGC
  - 📡 Optional MQTT bridge to extend alerts beyond the local mesh
  - 💾 Persistent SQLite history of every event, exportable anytime

  **Technologies**: Python, Flet, Meshtastic, MQTT, SQLite, PyInstaller

  [🔗 View Repository](https://github.com/sparveriusdev/AlertasSismosColombia)

  ---

### 🌧️  **InterporApp** - Hydrometeorological Interpolation Suite for IDEAM Data
  <img src="https://img.shields.io/badge/Platform-Windows-lightgrey?style=flat" />

  Desktop tool that spatializes and interpolates hydrometeorological variables from Colombia's IDEAM network — turns point measurements from scattered stations into continuous
  surfaces:
  - 📐 IDW, Ordinary Kriging and Universal Kriging, with optional DEM covariate for Universal Kriging
  - ✅ Automatic LOOCV cross-validation with metric reports on every run
  - 🗂️  Reads `.data` files + the CNE (Catálogo Nacional de Estaciones) to generate GeoPackage (GPKG) and GeoTIFF rasters
  - ✂️  AOI clipping (KML/KMZ/SHP/GPKG/GeoJSON) with automatic extent adjustment
  - ⚡ Parallel batch processing with pause/stop controls

  **Technologies**: Python, [confirm: GDAL/Rasterio? GeoPandas? PyKrige?], concurrent.futures

  [🔗 View Repository](https://github.com/sparveriusdev/interporapp)
  [📖 Read the article](https://skymapstories.com/blog/posts/geoestadistica-interpolacion-idw-kriging/)

### ✈️  **ADS-B Analyzer** - RAW Flight Data Decoder & GIS Export Tool
  <img src="https://img.shields.io/badge/Platform-Windows%20|%20macOS%20|%20Linux-lightgrey?style=flat" />

  CLI tool that decodes RAW ADS-B recordings from SDRAngel, computes real AGL (above-ground-level) altitude against a DEM, and exports ready-to-use GIS layers:
  - 📡 Decodes raw ADS-B frames into per-flight tracks (pyModeS)
  - 🏔️  Real AGL altitude from a SRTM/DEM GeoTIFF, with a fallback fixed elevation
  - 🗺️  Exports GeoPackage (points, trajectories, phase-colored segments), 3D KML for Google Earth, and per-flight CSVs
  - 📊 Auto-generated AGL/MSL profile charts per flight and per session
  - 🧭 Filter by ICAO, minimum position count, CRS (e.g. EPSG:9377 MAGNA-SIRGAS), and more via CLI flags

  **Technologies**: Python, pyModeS, GeoPandas, Rasterio, Shapely, Fiona, Matplotlib, Click, Rich

### 🎯 **TipologIA** - AI Cadastral Recognition System
<img src="https://img.shields.io/badge/Status-Production-success?style=flat" /> <img src="https://img.shields.io/badge/LADM--COL-Compliant-blue?style=flat" />

**Colombia's first artificial intelligence for cadastral property recognition**

- 🧠 Deep learning model for automatic building typology classification
- 🏘️ Compliant with LADM-COL cadastral data model
- 📊 Processes drone imagery and satellite data
- ⚡ Significantly reduces manual field survey time
- 🎯 Deployed in real cadastral operations across Colombia

**Technologies**: Python, TensorFlow, OpenCV, QGIS, PostgreSQL/PostGIS

[🔗 View Project](https://github.com/SESMAPS/Tipologia)



### 📱 **Mini 3 App** - DJI Mini 3/4/5 M3E Utilities Suite
<img src="https://img.shields.io/badge/Platform-Windows%20|%20macOS%20|%20Linux-lightgrey?style=flat" />

Professional toolkit for DJI Mini 3 drone operations:
- 📁 Automated file organization by date
- 🔋 Battery cycle tracking with interactive charts
- 🚁 Multi-drone fleet management
- 📊 Flight statistics and performance metrics
- 🗄️ SQLite database with full CRUD operations

**Technologies**: Python, Flet, Plotly, SQLite, Nuitka

[🔗 View Repository](https://github.com/sparveriusdev/mini3-app)

---

### 🗺️ **360x5 Aerial Processing Pipeline**

End-to-end photogrammetric processing system:
- 🎥 360° camera video frame extraction
- 📸 EXIF metadata management and GPX correlation
- 🗺️ Orthomosaic generation and georeferencing
- 📐 Topographic map creation with QGIS integration
- ⚡ Automated batch processing workflows

**Technologies**: Python, FFmpeg, ExifTool, GDAL, QGIS, Pix4D

---

## 🛠️ Tech Stack

<div align="center">

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### GIS & Geospatial
![QGIS](https://img.shields.io/badge/QGIS-589632?style=for-the-badge&logo=qgis&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![GDAL](https://img.shields.io/badge/GDAL-5CAE58?style=for-the-badge)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)

### AI & Machine Learning
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### DevOps & Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 📊 Industry Applications

### 🏛️ **Cadastre & Land Administration**
- LADM-COL model implementation
- Property recognition and classification with AI
- Cadastral database design and management
- Field survey optimization and automation

### 📐 **Topography & Surveying**
- Drone-based topographic surveys
- Ground control point (GCP) workflows
- Volume calculations and earthwork analysis
- Precision mapping and georeferencing

### 🏗️ **Construction & Urban Development**
- Progress monitoring with aerial imagery
- 3D modeling and BIM integration
- Site analysis and planning support
- As-built documentation

### 🏛️ **Architecture**
- Existing conditions documentation
- Facade analysis and inspection
- 3D visualization and presentation
- Heritage preservation documentation

### 🌱 **Precision Agriculture**
- Crop health monitoring (NDVI, NDRE)
- Field boundary mapping
- Irrigation planning support
- Yield estimation

---

## 🎓 Certifications & Standards

- ✅ **LADM-COL** - Colombian Land Administration Domain Model
- 🚁 **UAV/Drone Pilot** - Commercial operations
- 🗺️ **GIS Specialist** - QGIS, ArcGIS platforms
- 📊 **Photogrammetry Professional** - Pix4D, Agisoft certified workflows

---

## 📈 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=sparveriusdev&show_icons=true&theme=algolia&include_all_commits=true&count_private=true"/>

<img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=SESMAPS&layout=compact&langs_count=8&theme=algolia"/>

</div>

---

## 💡 What I'm Currently Working On

- 🚁 **SkyMapStories**: Building aerial photography brand and professional drone services
- 🤖 **Geospatial AI**: Exploring new applications of computer vision in cadastre and surveying
- 📱 **Open Source**: Contributing to GIS and photogrammetry tools
- 🎥 **Content Creation**: Sharing knowledge about drones, mapping, and technology

---

## 🤝 Let's Connect!

I'm always interested in collaborating on innovative geospatial projects, especially those involving:
- 🗺️ Cadastral systems and land administration
- 🤖 AI applications in surveying and mapping
- 🚁 Drone-based data acquisition and processing
- 📊 Spatial data analysis and visualization

### 📫 Contact Me

- 🌐 **Website**: [skymapstories.com](https://skymapstories.com)
- 📧 **Email**: contacto@skymapstories.com
- 💼 **LinkedIn**: [linkedin.com/in/davidvasquez](https://linkedin.com/in/davidvasquez)
- 📸 **Instagram**: [@skymapstories](https://instagram.com/skymapstories)
- 🎥 **YouTube**: [@skymapstories](https://youtube.com/@skymapstories)

---

## 💰 Support My Work

If you find my projects useful, consider supporting my work:

☕ **Buy Me a Coffee**: [buymeacoffee.com/sparverius](https://buymeacoffee.com/sparverius)

💎 **IOTA Donations**: `0xc3812b12ccff491cfe221e41d691f3beda07005845b6bd17950cfd25dd90657e`

---

<div align="center">

### 🌟 "Every flight tells a story, every map reveals a secret"

**Exploring heights, mapping realities**

</div>
