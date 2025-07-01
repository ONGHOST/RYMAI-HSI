# RYMAI-HSI
AI-enhanced hotspot forecasting Sardine Habitat Suitability - Atlantic Ocean (Moroccan Coast) based on HSI formula (HABITAT SARDINE INDEX)
RYMAI
AI-enhanced hotspot forecasting
Sardine Habitat Suitability - Atlantic Ocean (Moroccan Coast)
based on HSI formula (HABITAT SARDINE INDEX)
08 05 2025
This PDF is part of a working model
combining biological behavior,
oceanographic simulation, and
AI-enhanced hotspot forecasting..
![Alt text](images/Figure_005.png)
![Alt text](images/MOROCCAN-COAST-05.PNG)
![Alt text](images/SAFI-COAST-05.PNG)
This document summarizes the environmental indicators and a custom-built Habitat
Suitability Index (HSI) model for predicting optimal sardine aggregation areas along the
Moroccan Atlantic coast.
The system includes simulated data and real-world satellite sources (e.g., CMEMS,
Copernicus, GEBCO).
Key Indicators Modeled:
1. Chlorophyll-a (C): Proxy for plankton concentration. Optimal: 0.3-0.6 mg/m^3.
2. Sea Surface Temperature (T): Optimal sardine range: 16-17 degC.
3. Depth (D): Ideal sardine range: 20-200 meters (shelf and slope).
4. Canary Current Velocity (V): Flow brings nutrient-rich water along Moroccan coast (ideal: 0.1-0.3m/s).
5. Sea Level Anomaly (SLA): Proxy for upwelling/mesoscale eddies. Lower SLA (<0.15 m).
6. Ekman Upwelling Index (E): Indicates wind-driven upwelling; optimal 10-40 m^3/s/km.
7. Thermocline Depth (Th): Shallower thermocline (~20-50 m) increases productivity.
8. Distance from Coast: Sardines are generally neritic (<250 km from coast).
Custom Habitat Suitability Formula (HSI):
HSI = 0.2 * S_c(C) + 0.2 * S_t(T) + 0.15 * S_d(D) + 0.15 * S_v(V) + 0.1 * S_sla(SLA) +
0.1 * S_ekman(E) + 0.1 * S_thermo(Th) Each S_x().
is a scaled subfunction from 0 to 1, mapping the environmental variable to its suitability
for sardines.
3City Focus Points (Within 60 Miles):
- Safi: Latitude ~32.3N, Longitude ~-9.2E
- Agadir: Latitude ~30.4N, Longitude ~-9.6E
- Dakhla: Latitude ~23.7N, Longitude ~-15.9E
Mapped Points use highest HSI value within 96.5 km radius.
AI Model based on :
● Chlorophyll & SST
● Live Copernicus data
● Seasonal maps
● Depth masking @ETOPO1 @GEBCO.
● Salinity and zooplankton biomass
https://www.ncei.noaa.gov/maps/grid-extract/
https://www.ncei.noaa.gov/products/etopo-global-relief-model
https://www.ngdc.noaa.gov/mgg/global/relief/ETOPO1/data/bedrock/grid_registered/ne
tcdf/
https://www.gebco.net/data-products-gridded-bathymetry-data/gebco2024-grid#toc-g
ebco-type-identifier-tid-grid
https://cfconventions.org/software.html
https://marine.copernicus.eu/
https://oceandata.sci.gsfc.nasa.gov/
4
