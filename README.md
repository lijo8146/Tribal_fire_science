# Tribal Fire Mapping and Modeling: North America Datasets

This guide lists **open datasets and tools** that support **Tribal-led fire management, modeling, and research** across North America. It emphasizes spatial fire science while respecting **Tribal data sovereignty principles** and Indigenous governance.
---

## Base Geospatial Layers

| Layer | Source | Coverage | Notes |
|------|-------|----------|-------|
| Tribal Lands / Reservations | BIA Tribal Boundaries (U.S.), Native Land Digital | U.S., Canada | Define sovereign lands and cultural areas. Always confirm with local Tribal GIS offices. |
| Elevation / Terrain | USGS 3DEP, SRTM 30 m DEM | North America | Use for slope, aspect, and terrain-driven fire spread modeling. |
| Hydrology / Watersheds | USGS NHDPlus, Canadian Hydrographic Service | Continental | Important for fire breaks, riparian zones, and smoke transport. |
| Land Cover / Vegetation | LANDFIRE EVT/EVC, NLCD, ESA CCI Land Cover | North America | Vegetation composition and structure for fuels and fire behavior modeling. |

---

## Fire History & Activity

| Dataset | Description | Source | Temporal Coverage |
|-------|-------------|--------|------------------|
| MTBS | Burn severity and perimeters for large fires | MTBS.gov | 1984–present |
| NIFC Historical Fire Perimeters | National multi-agency perimeter dataset | data.nifc.gov | 1990–present |
| FRAP Fire Perimeters | Western U.S. wildfire polygons | CAL FIRE FRAP | 1878–present |
| Canadian Wildland Fire Information System (CWFIS) | National fire database and near-real-time maps | CWFIS | 1980–present |
| NASA FIRMS (MODIS & VIIRS) | Daily active fire detections (global) | FIRMS | 2000–present |

---

## Fuels, Vegetation, and Fire Behavior Inputs

| Dataset | Description | Source |
|-------|-------------|--------|
| LANDFIRE Fuel Models (FBFM40, FCCS) | Fire behavior fuel models for the U.S. | LANDFIRE.gov |
| USFS Forest Inventory and Analysis (FIA) | Tree composition and structure data | FIA |
| Canadian Forest Service Fuel Type Maps | Fuel classification for Canada | NRCan Open Data |
| NDVI / EVI Time Series | Vegetation greenness and drought stress | MODIS, Sentinel-2 (via Google Earth Engine) |

---

## Weather & Climate

| Dataset | Description | Source | Spatial / Temporal Resolution |
|-------|-------------|--------|-------------------------------|
| GRIDMET | Daily gridded weather data | GRIDMET | 4 km; 1979–present |
| PRISM | Historical and near-real-time climate normals | PRISM | 4 km; 1895–present |
| RAWS | Remote Automated Weather Stations | MesoWest RAWS Archive | Point-based; live |
| North American Drought Monitor | U.S.–Canada–Mexico drought extent | NOAA / CEC | Monthly |
| NARR / ERA5 Reanalysis | Atmospheric variables for wind & humidity | NOAA, Copernicus | Hourly to 3-hourly |

---

## Modeling-Ready Inputs

For use with **FARSITE, FlamMap, BehavePlus, or OpenWFM**.

| Input Layer | Typical Source |
|-----------|----------------|
| Elevation / Slope / Aspect | USGS DEM or SRTM |
| Surface Fuels | LANDFIRE Fuel Models |
| Canopy Cover / Height / Base Height | LANDFIRE or FIA |
| Wind & Weather Grids | GRIDMET or RAWS |
| Moisture / Drought Indices | PRISM, GRIDMET, NADM |

---

## Cultural and Ecological Integration (With Permission)

| Data Type | Source / Method | Notes |
|---------|----------------|-------|
| Cultural Burning Sites / Traditional Use Areas | Tribal GIS or Cultural Preservation Offices | Highly sensitive; require governance agreements. |
| Ecocultural Plant Distributions (e.g., sweetgrass, bear root) | Tribal data, ethnobotany surveys, GBIF species records | Supports fire planning that enables cultural regeneration. |
| Wildlife & Habitat Overlays | USGS GAP Analysis, NatureServe Explorer | Aligns fire management with ecological and species goals. |

---

## Analytical Tools & Platforms

| Tool | Use | Access |
|----|-----|--------|
| FARSITE / FlamMap / BehavePlus | Fire spread and behavior modeling | FireLab |
| QGIS / ArcGIS Pro | Spatial analysis and map creation | Open-source or licensed |
| Google Earth Engine | Cloud-based remote sensing and fire/NDVI trend analysis | Free for research |
| Python / R Packages | Modeling and data fusion (e.g., `rasterio`, `geemap`, `terra`, `sf`) | Reproducible workflows |
| Indigenous Data Cube Framework | Earth observation under Tribal governance | Customizable; aligns with CARE principles |

---

## Ethical & Sovereignty Considerations

- Follow **Tribal data governance protocols** and establish MOUs before mapping culturally significant areas.
- Apply **CARE Principles**: Collective Benefit, Authority to Control, Responsibility, Ethics.
- Respect **OCAP®** (Ownership, Control, Access, Possession) for First Nations data in Canada.
- Attribute all data sources appropriately and **maintain Tribal control** over sensitive spatial layers.

---

This reference is intended as a **starting point** for North American Tribal fire research, mapping, and modeling projects, supporting Indigenous-led stewardship and non-extractive science.

