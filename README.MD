## CMS Physician Data

All this work exists in the kubeflow env, specifically rahul-claims.

state.parquet contains the indexed parquet files
geojson-state contains the shapefiles
usa-zip-data contains another version of shapefiles

01. Generate Parquets.ipynb - Creates indices from source CMS data files, by state
02. Provider and service aggregates.ipynb - Main analysis notebook, contains aggregates by zip code and a majority of the exploratory work
folium_example-1616103379668.ipynb - Zacks sample folium code
Widget testing.ipynb - Some testing with widgets to visualize data in real time