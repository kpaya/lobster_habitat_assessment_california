# California Spiny Lobster: Habitat Assessment for Aquaculture Opportunities

## About

This repository contains a geospatial analysis to assess the suitability of habitats for spiny lobsters in California, with a particular focus on identifying areas most conducive to aquaculture development. Spiny lobsters are an economically significant species in the region, and their population are influenced by factors such as temperature and ocean depth. This study uses remote sensing technologies to integrate environmental data, including sea surface temperature and bathymetric data, to pinpoint areas that could support viable lobster farming operations.

## Repository Structure

The repository is organized as follows:

/data: Contains the raw datasets used in the analysis

README.md: This file provides an overview of the repository and how to use it.

lobster_habitat_geospatial_assessment.qmd: Quarto document containing the analysis,including data wrangling, spatial analysis, and suitability mapping for lobster farming.

## Data

1. Sea Surface Temperature:

The Sea Surface Temperature (SST) dataset from NOAA (2008-2012) provides daily global satellite-derived sea surface temperature anomalies at a 5 km resolution. This dataset is crucial for identifying areas with suitable temperature ranges for spiny lobsters, as their growth and habitat preferences are linked to specific water temperature conditions (14.8°C - 22.3°C). It is used to reclassify temperature data and pinpoint suitable lobster farming areas. These files can be found in the /data folder.

2. Bathymetry:

The General Bathymetric Chart of the Oceans (GEBCO) provides bathymetric data that describes the ocean's depth. This dataset is essential for evaluating the ocean depth of potential lobster habitats, as spiny lobsters prefer specific depth ranges (0-150 meters). Please note that due to the large file size, this dataset cannot be included in this repository. This file can be downloaded directly from the source, the link is provided below.

3. Exclusive Economic Zones (EEZs):

The Exclusive Economic Zones (EEZs) dataset from MarineRegions.org defines the marine boundaries of countries. This dataset is used to mask the suitable lobster habitat areas by region, ensuring that only locations within the jurisdictional boundaries of relevant EEZs are considered in the final suitability analysis. This dataset resides in the /data folder.

## References

Sea Surface Temperature

National Oceanic and Atmospheric Administration (NOAA). 2008-2012. 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1 \[Data set\]. NOAA National Centers for Environmental Information. Retrieved Nov. 14, 2024 from https://www.ncei.noaa.gov

Bathymetry

General Bathymetric Chart of the Oceans (GEBCO). 2024. gridded bathymetry data \[Data set\]. Retrieved Nov. 14, 2024 from https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area

Exclusive Economic Zones

MarineRegions.org. (n.d.). Exclusive Economic Zones (EEZs) off the west coast of the United States \[Data set\]. Retrieved Nov. 14, 2024 from https://www.marineregions.org/
