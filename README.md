# Health on Wheels: Cycling and Health Patterns

This project looks at how cycling infrastructure and real health data can be studied together. I used OSMnx to download real bike routes and a public health dataset to explore sleep, stress, and activity patterns.

## How to Run
1. Open the notebook `health_on_wheels.ipynb` in Google Colab.
2. Run all cells from top to bottom.
3. The code will download health data, download cycling routes, make maps, and create charts.
4. The maps and charts will be saved into the `outputs/` folder.

## Folder Structure
- `notebooks/health_on_wheels.ipynb` — main notebook with code and results  
- `health_data.csv` — cleaned health dataset  
- `cycling_routes.geojson` — cycling network from OSMnx  
- `maps/` — saved map images  
- `charts/` — saved charts  
- `documentation.pdf` — list of files with one-sentence descriptions  
- `README.md` — how to run and understand this project  

## Requirements
- Python  
- pandas  
- geopandas  
- osmnx  
- matplotlib  

## Known Issues
This project uses two separate datasets that are not linked to each other. The results are exploratory and meant to show how geospatial tools and health data can work together.
