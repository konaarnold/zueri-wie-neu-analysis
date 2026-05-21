# Züri wie neu analysis

Spatial analysis of infrastructure issues in Zurich using ZüriWieNeu data.

## Project overview

This project analyses reported infrastructure issues in Zurich between 2014 and 2025 using spatial and temporal analysis methods. The analysis combines infrastructure reports, statistical neighbourhood boundaries, and neighbourhood population data to investigate spatial patterns, temporal trends, and population-normalised reporting rates.

The project includes choropleth maps, categorical analysis, and temporal analyses of reporting patterns across the Zurich neighbourhoods.

## Data sources

- Züri wie neu reports
https://data.stadt-zuerich.ch/dataset/geo_zueri_wie_neu

- Statistical neighbourhoods
https://data.stadt-zuerich.ch/dataset/geo_statistische_quartiere

- Population data
https://data.stadt-zuerich.ch/dataset/bev_bestand_jahr_quartier_od3240

The reports and statistical neighbourhood datasets were downloaded on 04.05.2026.

The population dataset was downloaded on 12.05.2026

## Repository structure

data/raw/: raw datasets  
data/processed/: processed spatial datasets  
notebooks/: Jupyter notebook  
outputs/maps: exported maps

## Setup

The analysis was created using the sds-env conda environment.

The complete environment can be recreated using the provided environment.yml file.
Required Python packages:

- pandas
- geopandas
- matplotlib

## Execution

GitHub repository:

https://github.com/konaarnold/zueri-wie-neu-analysis.git

Run the notebook:

notebooks/zueri_wie_neu_analysis.ipynb

Execute all cells from top to bottom.

## AI use disclosure 

I used ChatGPT (OpenAI GPT-5.5) as an assistance tool during the preparation of this project to improve grammar and linguistic clarity, refine markdown explanations, improve code structure and readability, debug code, and improve the visual design and formatting of maps and graphs.

All AI-assisted code, analysis decisions, interpretations, and written content were critically reviewed, edited, verified, and fully understood by me before submission.