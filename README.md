# zueri-wie-neu-analysis

Spatial analysis of infrastructure issues in Zurich using ZüriWieNeu data.

## Project overview

This project analyses reported infrastructure issues in Zurich using spatial and temporal analysis methods. The analysis combines infrastructure reports, statistical neighbourhood boundaries, and neighbourhood population data to investigate spatial patterns, temporal trends, and population-normalized reporting rates.

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
notebooks/: Jupyter notebook  
outputs/: exported figures and maps

## Setup

Required Python packages:

- pandas
- geopandas
- matplotlib

The analysis was created using the sds-env conda environment.

The complete environment can be recreated using the provided environment.yml file.

## Execution

Run the notebook:

notebooks/zueri_wie_neu_analysis.ipynb

Execute all cells from top to bottom.

## Limitations

The analysis is based on reported infrastructure issues and may not represent all existing problems in the city. Reporting activity can be influenced by population density, public awareness, and user behaviour.

The population-normalized analysis improves comparability between neighbourhoods but does not account for commuters, tourists, or daytime population differences.
