# Strategic Analytics for EV Charging Infrastructure in Ireland

**Module:** Strategic Thinking (Higher Diploma in Data Analytics for Business)  
**Institution:** CCT College Dublin  
**Lecturer:** Taufique Ahmed (`tahmed1986`)  
**Assessment:** CA1 – Capstone Project Proposal  
**Author:** Sujita Singh (sba26094)  

---

## 📌 Project Overview
This repository contains the capstone project proposal and implementation assets for predicting regional Electric Vehicle (EV) charging demand across Ireland. 

Aligned with Ireland’s Climate Action Plan to support 950,000 EVs by 2030, this project addresses the strategic challenge local authorities and energy providers face: **optimizing the spatial distribution of EV charging infrastructure to prevent grid congestion and service bottlenecks.**

---

## 📊 Data Sources
The primary datasets utilized in this project are sourced from [data.gov.ie](https://data.gov.ie) under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** open-data license:

1. **CSO Vehicle Registrations (`TEA30`):** Regional EV stock and historical adoption trends across Irish counties.
2. **CSO Public EV Charging Points (`PCIEV01`):** Infrastructure distribution and charger classification (Standard vs. Fast).
3. **Local Authority Open GIS Datasets (Smart Dublin / Local Councils):** Geolocation data, charger types, and capacity metrics.

---

## 🏗️ Repository Structure

```text
├── docs/
│   ├── sba26094_CA1_Strategic_Thinking_v1.docx   # Main 1,500-word Proposal Report
│   ├── sba26094_CA1_AI_Declaration_v1.docx       # Completed AI Declaration
│   └── sba26094_CA1_Ethics_Form.pdf              # Signed Ethics Approval Form
├── data/
│   ├── raw/                                 # Raw datasets downloaded from data.gov.ie
│   └── processed/                           # Cleaned & transformed datasets (Semester 2)
├── notebooks/                               # Jupyter Notebooks for EDA & Preprocessing (Semester 2)
├── models/                                  # Trained predictive models (Semester 2)
├── src/                                     # Data pipeline & feature engineering scripts
└── README.md                                # Project documentation
