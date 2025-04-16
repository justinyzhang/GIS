
# Budapest Electoral Geography Analysis

This project analyzes the spatial distribution of political support and voter turnout in Budapest using voting station-level data from the European Parliament election.

## Project Objective

To identify spatial patterns in voter behavior, particularly:
- The clustering of support for the ruling party (FIDESZ) and opposition
- Spatial autocorrelation in voter turnout
- Signs of political polarization across different urban areas

## Methods Used

- Vector data processing with GeoPandas
- Geometry cleaning and coordinate system handling
- Spatial joins and attribute calculations
- Spatial autocorrelation analysis (Moran's I) using PySAL
- Thematic mapping with Matplotlib

## Data

- Input file: `epvalasztascount.geojson`
- Contents: voting station geometries, turnout data, and vote counts by party
- CRS: EPSG:4326

## Project Files

- `GDS.ipynb`: main analysis notebook
- `data/epvalasztascount.geojson`: source data
- `output/`: generated maps and tables

## How to Run

Place the dataset in a `data/` folder and open the notebook
