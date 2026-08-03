# Evaluating Calgary Transit's Downtown Corridor

Analysis of Calgary Transit's CTrain system (Red 201 & Blue 202 lines) using GTFS data to measure passenger wait times and visualize downtown service metrics.

## Features
- **GTFS ETL:** Downloads and parses static GTFS data into SQLite (`ctrain.db`).
- **Wait Time Metrics:** Calculates headways, Scheduled Wait Time (SWT), and variance penalties.
- **Geospatial Mapping:** Generates interactive Folium maps highlighting Downtown Free Fare Zone stations.

## Quickstart

```bash
# Clone & install dependencies
git clone https://github.com/AmritpalSaini1/Evaluating-Calgary-Transit-s-Downtown-Corridor.git
cd Evaluating-Calgary-Transit-s-Downtown-Corridor
pip install pandas numpy requests sqlalchemy folium geopandas shapely jupyter

# Run analysis
jupyter notebook gtfs_calgary.ipynb
```

## Structure
- `gtfs_calgary.ipynb` - Main data pipeline and visualization notebook.
- `data/ctrain.db` - SQLite database generated during execution.
