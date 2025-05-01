# Estimating the Energy Consumption of Data Centres in the European Union

This repository contains the complete code, processed datasets, and outputs developed for my Master's thesis **"Estimating the Energy Consumption of Data Centres in the European Union: Policy Implications for AI Deployment and Sustainability"**

The project uses a bottom-up and area-based model to estimate:
- Annual energy consumption (TWh/year)
- Associated CO₂ emissions (tons/year)

Final outputs include energy and emissions estimates under three scenarios (low/mid/high), with cluster detection and national aggregation.

## Repository Structure

```bash
thesis-dc-emissions/
├── input/           # Input data folders (not all files provided due to confidentiality)
├── output/          # Anonymized outputs and intermediate files
├── figures/         # Final figures and plots
├── code/            # Jupyter notebooks 
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

## Data Availability

Some inputs cannot be shared due to confidentiality constraints. However, the final anonymized spatial dataset is available here: `/output/data_center_emissions_anonymized.geojson`

/output/data_center_emissions_anonymized.geojson
It includes country-level classification, scenario-based energy and emissions values, and obfuscated geometry.

##  License and Usage

This repository is intended for academic research purposes only.
