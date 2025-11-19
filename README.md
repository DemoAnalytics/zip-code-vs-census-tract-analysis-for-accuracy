<p align="center">
  <img src="thumbnail.png" width="500">
</p>

# Census Tract vs ZIP Code Analysis for Dane County, Wisconsin

This repository contains a demographic analysis comparing **Census Tracts** and **ZIP Codes** as units of geographic analysis, using Dane County, Wisconsin as a case study.

ZIP codes are commonly used in public health, planning, and equity work, but they often **mask substantial internal socioeconomic variation**. This project demonstrates why **Census Tracts** provide a more accurate and informative geography for data-driven decision-making.

---

## 📄 Full Report (PDF)

**Download and read the full report here:**  
➡️ [Census Tract vs ZIP Code Analysis – Dane County](reports/tract_vs_zip_analysis.pdf)

This document includes:  
- A methodological explanation of ZIP Codes vs Census Tracts  
- ACS workflows using tract-level data  
- Visualizations comparing tract vs ZIP medians  
- A case study showing how ZIP Code 53593 masks within-area disparities  
- Maps and charts produced using **tidycensus**, **tidyverse**, and **QGIS**  
- Recommendations for planners, nonprofits, and policy analysts  

---

## 🔍 Key Findings

- ZIP Code **53593** reports a median household income of **$130,289**  
- When aggregating the **Census Tracts** inside that ZIP, the true combined median income is **$85,377**  
- That’s a **$44,912 difference**, illustrating how ZIP-level analysis can **overstate local socioeconomic conditions**  
- Census Tracts provide more accurate, neighborhood-scale insight  
- ZIP Codes should be avoided for equity analysis, needs assessments, and targeted funding decisions  

---

## 🛠️ Methods and Tools

This project uses:  
- **R (tidycensus, tidyverse)** for ACS data extraction and analysis  
- **QGIS** for mapping and spatial visualization  
- **R ggplot2** for statistical graphics  
- **B19001 Household Income Distribution** to reconstruct aggregate medians  

---

## 📬 Work With Me

If you need:  
- demographic analysis  
- ACS data workflows  
- neighborhood-level socioeconomic mapping  
- equity indicators  
- custom GIS or R-based reporting  

I’m available for consulting and project-based work.  
👉 **Hire me on Upwork:**  
[https://www.upwork.com/freelancers/demoanalytics](https://www.upwork.com/freelancers/demoanalytics)  

---

## 📜 License

This repository and its contents (plots, text, maps, and the PDF report) are released under the  
**Creative Commons Attribution–NonCommercial 4.0 International License (CC BY-NC 4.0).**  
This allows sharing with attribution, but **no commercial use**.  
Full license: [https://creativecommons.org/licenses/by-nc/4.0/](https://creativecommons.org/licenses/by-nc/4.0/)  

---
