# Final Project
# Mesoscale Eddies and Surface Chlorophyll Variability in the Offshore Gulf of Mexico

### Celina Gong | xg2467

## Scientific Question
How do mesoscale eddies influence surface chlorophyll variability in the offshore Gulf of Mexico?

## Hypothesis
***Cyclonic eddies*** identified from *negative sea surface height anomalies* (SSHA) are expected to be associated with higher surface chlorophyll anomalies, while ***anticyclonic eddies*** identified from *positive SSHA* are expected to be associated with lower surface chlorophyll anomalies in the offshore Gulf of Mexico.

## Datasets
### Eddy datasets
- [Copernicus Marine Global Ocean Gridded L4 Sea Surface Heights and Derived Variables NRT (SEALEVEL_GLO_PHY_L4_NRT_008_046)](https://data.marine.copernicus.eu/product/SEALEVEL_GLO_PHY_L4_NRT_008_046/description)
- [Mesoscale Eddy Trajectory Atlas Product](https://www.aviso.altimetry.fr/en/data/products/value-added-products/global-mesoscale-eddy-trajectory-product.html)

### Chlorophyll datasets
- [NASA Ocean Color Level 3 & 4 Browser](https://oceancolor.gsfc.nasa.gov/l3/)
- [Copernicus Marine Global Monthly Chlorophyll-a Product (OCEANCOLOUR_GLO_BGC_L4_MY_009_104)](https://data.marine.copernicus.eu/product/OCEANCOLOUR_GLO_BGC_L4_MY_009_104/description)


## Summary of Analysis
I will analyze satellite data products SSHA and chlorophyll-a over the offshore Gulf of Mexico using Xarray and Pandas in Python. Then I will subset the study region, align the two datasets in space and time, compute monthly chlorophyll anomalies by removing the monthly climatology, and classify cyclonic and anticyclonic eddies based on sea surface height anomaly. Finally, I will compare chlorophyll anomaly patterns across eddy regimes using maps, seasonal summaries, and grouped statistical plots.

## Code Structure
1. Load the SSHA and chlorophyll-a datasets.
2. Subset both datasets to the offshore Gulf of Mexico study region and align them in space and time.
3. Compute monthly chlorophyll climatology and remove the seasonal cycle to calculate chlorophyll anomalies.
4. Define cyclonic and anticyclonic eddies using SSHA.
5. Create maps and summary plots to compare chlorophyll anomaly patterns across two eddy types.


