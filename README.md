# 🗺️ OSM Data Extraction & ETL Pipeline  
### Internship Project — Webeet.io (2 Months)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 🎯 Project Objective
Extract and process **cultural points of interest** from **OpenStreetMap (OSM)** for the city of **Berlin**, transforming raw geospatial data into a structured format ready for **database integration and analysis**.

---

## 🛠️ Tools & Technologies

### 💻 Languages & Libraries
- Python  
- pandas  
- geopandas  
- osmnx  

### 🗄️ Databases
- PostgreSQL  

### 📊 Development Environment
- Jupyter Notebook (data exploration, analysis, and prototyping)

---

## 🔄 ETL Pipeline Overview

### 📥 Data Extraction
- Pulled geospatial data from the **OSM API** for:
  - 🖼️ Galleries  
  - 🏛️ Museums  
  - 🎨 Public Artworks  
  - 🏢 Exhibition Centers  

### 🧹 Data Cleaning & Transformation
- Normalized raw OSM data for consistency and reliability  
- Filtered and standardized attributes to align with **database schema requirements**  
- Handled missing values, geometry validation, and category mapping  

### 📤 Data Loading
- Loaded processed datasets into a **PostgreSQL** database  
- Created reusable scripts for automated data ingestion  

---

## 📦 Deliverables
- Python scripts for OSM data extraction  
- Data cleaning and transformation pipeline  
- PostgreSQL loading utilities  
- Structured, analysis-ready datasets  

---

## 🖼️ Workflow Diagram
```mermaid
flowchart TD
    A[OSM API] --> B[Data Extraction Scripts]
    B --> C[Data Cleaning & Transformation]
    C --> D[PostgreSQL Database]
    D --> E[Analysis & Reporting]
```

## 🚀 Highlights

- Automated ETL pipeline for geospatial data

- Scalable scripts for repeated use across different OSM categories

- Ensured clean, consistent, and analysis-ready datasets for downstream applications


