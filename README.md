# Hamilton Public Facilities Accessibility Analysis

This project conducts a spatial analysis to evaluate the accessibility of key public facilities—**schools**, **medical services**, and **parks**—for **residential areas in Hamilton City, New Zealand**. The goal is to identify which areas are underserved and to support more equitable urban planning.

##  Research Question

**Which residential areas in Hamilton City are currently underserved by public facilities?**

---

##  Project Overview

Ensuring equitable access to healthcare, education, and green space is essential for quality of life—especially for seniors and vulnerable populations. This project compares two GIS-based accessibility methods:

- **Method 1: Buffer + Union + Select**  
  Evaluates potential service coverage using Euclidean distance.
  
- **Method 2: Network Analyst (Service Area)**  
  Reflects real-world walkable access via the road network.

---

##  Methodology

- Selected public facilities: **Schools**, **Hospitals (incl. GP Clinics)**, and **Parks**
- Defined 500-meter accessibility zones
- Clipped and analyzed residential areas in Hamilton
- Classified service zones into **low**, **moderate**, and **high** accessibility levels
- Compared results between the two methods
- Produced visualized maps for interpretation

---

##  Key Findings

- **Low-accessibility areas** dominate much of the city, especially when real travel paths are considered.
- **Comprehensive accessibility (to all 3 types of facilities)** is limited—only **1.85 million m²** (Network Method), compared to **4.65 million m²** (Buffer Method).
- The **Network Method** offers a more realistic and conservative view of accessibility than the Buffer-based method.

---

##  Limitations

- Population demand and traffic conditions were not considered.
- Facility classification was general (e.g., no distinction between large and small parks).
- Edge/boundary effects may influence accuracy near city limits.

---

##  Future Work

- Integrate **population density** or **resident distribution models**
- Use **travel time** instead of distance for more realistic modeling
- Include **additional facility types** and finer classification
- Link results to **urban planning** strategies and **infrastructure development**

---

##  Data Sources

| Dataset                     | Source |
|----------------------------|--------|
| Hamilton City Boundary     | [Stats NZ](https://datafinder.stats.govt.nz/layer/120963-territorial-authority-2025/) |
| Schools                    | [LINZ Data Service](https://data.linz.govt.nz/layer/105588-nz-facilities/) |
| Hospitals (compiled)       | [Healthpoint](https://www.healthpoint.co.nz/) |
| Residential Areas          | [LINZ Data Service](https://data.linz.govt.nz/layer/50325-nz-residential-area-polygons-topo-150k/) |
| Parks (Reserves)           | [Waikato Open Data Hub](https://data-waikatolass.opendata.arcgis.com/) |

---

##  References

This work is supported by several academic studies, including:

- Wood et al. (2025), *BMC Public Health*
- Lotfi & Koohsari (2009), *Social Indicators Research*
- Nicoletti et al. (2022), *Environment and Planning B*
- Yhee et al. (2021), *Applied Sciences*
- Chen et al. (2022), *Spatial Information Research*

---

##  Author

Gongfan Zhang  
University of Waikato, 2025

---


