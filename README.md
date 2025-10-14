# Air Quality Trends and Health Impact in the U.S.

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🧭 Overview
This project investigates **air pollution trends across the United States (1980–2022)** — exploring temporal and spatial patterns in **Air Quality Index (AQI)** and their relationship with health outcomes such as **asthma** and **lung cancer**.  

We combine AQI, CO₂ emissions, climate disaster, and mortality datasets to:  
- Identify pollution hotspots  
- Examine pollutant–health relationships  
- Forecast air quality trends to 2050 using **Prophet**

> **Central Question:** Are we doing enough to secure breathable air for the future?

---

## 🔍 Research Questions
1. How has AQI evolved across U.S. states from 1980–2022?  
2. Which pollutants (PM2.5, O₃, NO₂, etc.) have the greatest health impact?  
3. What are the geographic differences in air quality?  
4. How strongly is pollution linked to asthma and lung cancer mortality?  
5. What will air quality look like by 2050?

---

## 🌱 Why This Matters
- **Policy Insight:** Supports evidence-based environmental reforms.  
- **Public Health:** Guides early interventions for high-risk regions.  
- **Education:** Raises awareness of pollution–health relationships.  
- **Forecasting:** Enables proactive air-quality management.  
- **Resource Allocation:** Identifies regions needing monitoring investments.  

---

## 📊 Data Sources
| Dataset | Description |
|----------|--------------|
| AQI (1980–2024) | U.S. Air Quality Index data |
| World Pollution Data | Global pollutant concentration |
| Mortality Data | Asthma & lung cancer deaths |
| GDP / Income | Socioeconomic correlates |
| CO₂ Emission Data | Emissions by sector (1980–2024) |

---

## 🧾 References
- **Burke et al. (2021)** – *PNAS*: *The changing risk and burden of wildfire smoke in the U.S.*  
- **Cohen et al. (2017)** – *The Lancet*: *Global burden of disease attributable to ambient air pollution.*  
- **Taylor & Letham (2018)** – *Forecasting at Scale (Prophet Model)*  

---

## ⚙️ Tools & Libraries
| Tool | Purpose |
|------|----------|
| **Python** | Analysis and visualization |
| **Pandas / NumPy** | Data cleaning & processing |
| **Matplotlib / Seaborn / Plotly** | Data visualization |
| **Prophet** | Forecasting AQI trends |
| **Google Colab** | Interactive environment |

---

## 🧩 Analysis Highlights
### 1️⃣ State-Wise AQI Trends
- Industrial states (CA, TX, IL) improved post-2005 with EPA reforms.  
- Rural states maintain lower AQI except during wildfire years.  

### 2️⃣ AQI Days Distribution
- “Good Air Days” increased sharply after the 1990s.  
- Pollution spikes correspond with wildfires and droughts.  

### 3️⃣ Geographic AQI Hotspots
- Persistent high-AQI zones in **California** and **Midwest**.  
- Low AQI in northern and mountain states.  

### 4️⃣ Climate Disasters
- Wildfires and storms drive pollutant surges.  
- Disasters have tripled since 2000, mirroring AQI instability.  

### 5️⃣ CO₂ Emission Trends
- Coal emissions dropped post-2010.  
- Oil and gas remain key contributors.  

### 6️⃣ Health Impact
- High NO₂ / PM2.5 ↔ higher asthma mortality.  
- Industrial and dense states most affected.  

### 7️⃣ Forecast (to 2050)
- Gradual improvement expected if clean-energy policies persist.  
- Climate-driven disasters may offset progress in specific regions.  

