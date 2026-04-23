## Chennai Healthcare Access Analyzer 🏥🗺️

A GIS-based spatial analysis project that maps healthcare infrastructure 
across Chennai and identifies underserved zones using K-Means clustering.
Built as part of my GIS application portfolio targeting smart governance and Digital India initiatives.



## 📌 Problem Statement

Which areas of Chennai lack adequate hospital access?

Government and city planners need data-driven insights to decide **where** 
to build new hospitals. This project answers that question visually using 
geographic data and machine learning.



## 🗺️ Live Map Preview

Open `chennai_healthcare_map.html` in any browser to view the 
full interactive map.

**Map features:**
- 🟢 Government Hospitals
- 🔵 Private Hospitals  
- 🟠 ESI Hospitals
- ⭕ Zone clusters with underserved area highlights
- 📋 Click any pin → hospital details (beds, doctors, emergency)
- 🔁 Toggle layers on/off



## 📊 Key Findings

- **50 hospitals** mapped across Chennai
- Chennai divided into **6 geographic zones** using K-Means clustering
- - **Zone 0 and Zone 5** identified as underserved (less than 6 hospitals)
- Areas include Tambaram, Poonamallee and Gerugambakkam with critical coverage gaps
- Outer Chennai areas have significantly fewer hospitals per population
- Government hospitals have the highest bed capacity on average
- Several outer zones have fewer than 6 hospitals serving large populations



## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming |
| Pandas | Data loading and analysis |
| Scikit-learn | K-Means clustering (ML) |
| Folium | Interactive map visualization |
| Matplotlib | Bar charts and EDA plots |
| Google Colab | Development environment |



## 🧠 How It Works

### 1. Data
50 Chennai hospitals with location coordinates, bed count, 
type (Govt/Private/ESI), and emergency availability.

### 2. Exploratory Data Analysis
- Hospital distribution by type
- Average beds per hospital type
- Emergency availability coverage

### 3. K-Means Clustering (ML)
- Input: latitude and longitude of each hospital
- Output: 6 geographic zones
- Zones with fewer than 6 hospitals flagged as underserved
- Cluster centers marked on map showing coverage gaps

### 4. GIS Visualization
- Interactive Folium map centered on Chennai
- Color-coded markers by hospital type
- Zone overlay showing underserved areas
- Popup details on every hospital


## 🚀 How to Run

1. Open `chennai_healthcare_gis.ipynb` in Google Colab
2. Run all cells in order
3. Map renders inside Colab
4. Download `chennai_healthcare_map.html` to view in browser



## 💡 Real-World Application

This type of spatial analysis is directly used in:
- **Smart City planning** — identifying infrastructure gaps
- **e-Governance dashboards** — visualizing public services
- **Disaster management** — mapping nearest medical facilities
- **Digital India initiatives** — healthcare access for all citizens



## 👩‍💻 Author

Iniya G
ECE Graduate 

---

## 📁 Project Structure
