# Estimating the Energy Consumption of Data Centres in the European Union

This repository contains the complete code, processed datasets, and outputs developed for the Master's thesis project titled:

**"Estimating the Energy Consumption of Data Centres in the European Union: Policy Implications for AI Deployment and Sustainability"**

The project builds a spatially explicit, bottom-up model to estimate:
- Annual energy consumption (TWh/year)
- Associated CO₂ emissions (tons/year) 

for over 1,600 data centers across the EU27, using facility data, geolocation, whitespace estimates, and electricity grid carbon intensity.

## Repository Structure

```bash
thesis-dc-emissions/
├── input/           # Input data folders (not all files provided due to confidentiality)
├── output/          # Anonymized outputs and intermediate files
├── figures/         # Final figures and plots
├── code/            # Jupyter notebooks and Python scripts
├── requirements.txt # Required libraries
└── README.md        # This file
```

## Code Modules

**code/** contains the step-by-step notebooks:

- `01_extract_urls.ipynb` — Sitemap parsing and URL extraction
- `02_scraping_pipeline.ipynb` — Scraping public data center pages
- `03_data_cleaning_feature_extraction.ipynb` — Feature extraction and preprocessing
- `04_energy_estimation_area_based.ipynb` — Energy modeling based on ITD and area class
- `05_carbon_intensity_mapping.ipynb` — Joining data centers with bidding zones and CI data
- `06_emissions_calculation.ipynb` — CO₂ emissions estimation per scenario
- `07_visualization_hotspots_energy_shares.ipynb` — EU-level maps and scenario analysis
- `08_anonymization_geojson.ipynb` — Anonymization of final GeoJSON

##  License and Usage

This repository is intended for academic research purposes only.
