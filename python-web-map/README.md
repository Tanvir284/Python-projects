# Python Web Map

This folder contains a simple project that generates an interactive HTML map using **Folium**.

## Overview

`app2-web-map.py` loads volcano location data and world population polygons to build a map. Volcano markers are colored by elevation and country polygons are colored by population.

The resulting map is saved as `Map.html` and can be opened in any web browser.

## Setup

Install the required packages with:

```bash
pip install pandas folium
```

## How to Run

Execute the script from this directory:

```bash
python app2-web-map.py
```

After it finishes, open the generated `Map.html` file in your browser to explore the map.

## Datasets

- **`Volcanoes_USA.txt`** – a CSV-style text file containing latitude, longitude and elevation information for volcanoes in the United States.
- **`world.json`** – GeoJSON data with country boundaries and population statistics used for the population layer.

