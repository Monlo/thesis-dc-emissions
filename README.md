# Estimating the Energy Consumption of Data Centres in the European Union

This repository contains the complete code developed for my Master's thesis project **_"Estimating the Energy Consumption of Data Centres in the European Union: Policy Implications for AI Deployment and Sustainability"_**

The project builds a spatially explicit, bottom-up model that estimates:
- Annual energy consumption (TWh/year)
- Associated CO₂ emissions (tons/year) for data centers across the EU27 countries.

## Repository Structure
- 01_extract_urls.ipynb — Sitemap parsing and URL extraction.
- 02_scraping_pipeline.ipynb — Scraping of public data center information.
- 03_data_cleaning_feature_extraction.ipynb — Data cleaning and feature extraction.
- 04_energy_estimation_area_based.ipynb — Energy consumption estimation by area classes.
- 05_carbon_intensity_mapping.ipynb — Assigning grid carbon intensities to data centers.
- 06_emissions_calculation.ipynb — CO₂ emissions modeling.
- 07_visualization_hotspots_energy_shares.ipynb — Hotspot mapping, country-level and EU27-wide summaries.
- 08_anonymization_geojson.ipynb — Final anonymization step.

## Data Availability

Some input datasets are **not included** in this repository for confidentiality reasons. However, the following public and anonymized outputs is included: `data_center_emissions_anonymized.geojson`

## License and Usage

This repository is intended for academic research purposes only.
