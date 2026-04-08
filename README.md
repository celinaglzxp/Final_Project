# Final Project
# Mesoscale Eddies and Surface Chlorophyll Variability in the Offshore Gulf of Mexico

### Celina Gong | xg2467

## Scientific Question
How do mesoscale eddies influence surface chlorophyll variability in the offshore Gulf of Mexico?

## Hypothesis
Cyclonic-like conditions identified from negative sea surface height anomalies are expected to be associated with higher surface chlorophyll anomalies, while anticyclonic-like conditions identified from positive sea surface height anomalies are expected to be associated with lower surface chlorophyll anomalies in the offshore Gulf of Mexico.

## Datasets
### Eddy datasets
- [Copernicus Marine Global Ocean Gridded L4 Sea Surface Heights and Derived Variables NRT (SEALEVEL_GLO_PHY_L4_NRT_008_046)](https://data.marine.copernicus.eu/product/SEALEVEL_GLO_PHY_L4_NRT_008_046/description)
- [Mesoscale Eddy Trajectory Atlas Product](https://www.aviso.altimetry.fr/en/data/products/value-added-products/global-mesoscale-eddy-trajectory-product.html)

### Chlorophyll datasets
- [NASA Ocean Color Level 3 & 4 Browser](https://oceancolor.gsfc.nasa.gov/l3/)
- [Copernicus Marine Global Monthly Chlorophyll-a Product (OCEANCOLOUR_GLO_BGC_L4_MY_009_104)](https://data.marine.copernicus.eu/product/OCEANCOLOUR_GLO_BGC_L4_MY_009_104/description)


## Summary of Analysis
I will analyze satellite-derived sea surface height anomaly and chlorophyll-a data over the offshore Gulf of Mexico using Xarray and Pandas in Python. I will subset the study region, align the two datasets in space and time, compute monthly chlorophyll anomalies by removing the monthly climatology, and classify cyclonic-like and anticyclonic-like conditions based on sea surface height anomaly. I will then compare chlorophyll anomaly patterns across eddy regimes using maps, seasonal summaries, and grouped statistical plots.

## Code Structure
1. Load the sea surface height anomaly and chlorophyll-a datasets.
2. Subset both datasets to the offshore Gulf of Mexico study region and align them in space and time.
3. Compute monthly chlorophyll climatology and remove the seasonal cycle to calculate chlorophyll anomalies.
4. Define cyclonic-like and anticyclonic-like conditions using sea surface height anomaly.
5. Create maps and summary plots to compare chlorophyll anomaly patterns across eddy regimes.
6. Use the AVISO eddy product as a supplementary reference to visualize eddy locations and support interpretation of the results.

