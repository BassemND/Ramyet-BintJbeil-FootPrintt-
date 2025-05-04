# 🗺️ Urban Footprint Mapping – Ramyet (Bint Jbeil, Lebanon)

## 📍 Overview
This project was part of my GIS work with **UN-Habitat Lebanon**, where I digitized the built-up area in **Ramyet village**, located in the Bint Jbeil District in southern Lebanon. I used **QGIS** and **Bing satellite imagery** to manually trace structures and analyze the urban footprint.

The goal was to visualize the **extent of built-up areas** within the cadastre for potential use in post-conflict analysis, urban planning, and humanitarian research. The mapping was completed during the **September 2024 war in Lebanon**.

The Bing imagery used was captured **before the conflict**, so this map serves as a **baseline reference** of existing structures in the area.

---

## 🎯 Objective
The urban footprint layer may support:
- Estimate the extent of construction within the cadaster
- Provide spatial data that could help analyze war-related damage or urban change
- Support potential humanitarian planning, mapping, or research

---

## 🛠 Tools & Methods

- **Software**: QGIS
- **Imagery**: Bing Satellite Imagery (pre-war)
- **Technique**: Manual digitization of built-up areas using QGIS editing tools
- **Source Layer**: Cadaster boundary shapefile for Ramyet

## 🧪 Methodology

1. I loaded the Ramyet cadastre shapefile and Bing imagery into QGIS.
2. Using the digitizing tool, I traced each visible structure manually — building a polygon layer of built-up areas.
3. I calculated the area of each polygon using the QGIS field calculator, then summed the results.
4. I exported two map screenshots:
   - One showing the cadastre boundary on the satellite image
   - One showing the built-up areas I digitized
   - Saved the screenshots as PNG images and added them to the `Maps/` folder.
   - Included the final digitized shapefile (with `.shp`, `.shx`, `.dbf`, `.prj`) in the `Data/` folder for demonstration purposes.

This was a hands-on project that helped me practice real GIS mapping workflows under real-world conditions.

### Key Stats:
- **Total Cadastre Area**: 6.120 km²  
- **Built-up Area**: 0.111 km²  
- **Urbanization Ratio**: ~1.81%

---

## 📐 Area Statistics
| Area Type       | Value (km²) |
|-----------------|-------------|
| Total Cadastre  | 6.120       |
| Built-up Area   | 0.111       |
| Built-up Ratio  | ~1.81%      |

These figures were calculated from manually digitized polygons using the QGIS field calculator and zonal statistics.

---

## 📚 Supporting Documents

The `Docs/` folder contains additional reference materials and visuals used in this project:

- `lebanon_cadasters_attributes.xlsx`: Full attribute table for all cadastres in Lebanon.
- `ramyet_cadaster_info.xlsx`: Specific attribute data for Ramyet cadastre.
- `ramyet_area_barchart.jpg`: A bar chart comparing:
  - Total area of Ramyet cadastre (6.120 km²)
  - Digitized built-up area (0.111 km²)

These documents support the area calculation results and help contextualize the urbanization level within the village boundary.

### 📊 Area Comparison Bar Chart
![Area Chart](Docs/ramyet_area_barchart.jpg)


---

## 🧭 Outputs
- A shapefile representing the urban footprint (`Data/` folder)
- Screenshot maps (`Maps/` folder)
- Project documentation in this README

---

## 📂 Folder Structure



---

## 🔒 Note on Data Use
This digitization is based on **public satellite imagery** and is **not linked to confidential datasets**. The work was performed as part of a supervised work and is presented here in a **reconstructed, portfolio-appropriate format**.

---

## 👤 About Me
**Bassem Jaafar Naser Aldine**  
Master's in Surveying Engineering – Lebanese International University  
📧 Bassem Naser Aldine | 🌐 www.linkedin.com/in/bassem-naser-aldine-402b0165

