# 3D-Visualization-of-California's-Road-Network

## Introduction
This Jupyter Notebook has been meticulously developed to enhance the analysis and visualization of California's vast road network via an interactive 3D model on Google Earth. At the heart of our endeavor lies the ambitious goal of amalgamating diverse datasets—ranging from OpenStreetMap for roadway infrastructure to FABDEM for elevation nuances, coupled with localized traffic information. Our vision was to craft a multifaceted tool poised to revolutionize urban planning and elevate traffic safety standards. The crowning achievement of this project is the creation of a scalable, precise model that adeptly captures the essence of traffic congestion, bottlenecks, and accident-prone zones, all encapsulated within an intuitive, user-centric interactive platform.

## Prerequisites
- Python 3.10
- Access to Google Colab (preferable for ease of use and access to resources)
- Required Python packages: osmnx, rasterio, gdal, pandas, numpy, networkx, warnings, itertools, geopandas, geopy, matplotlib

## Installation
1. If not using Google Colab, install Python 3.10 from [Python's official website](https://www.python.org/downloads/).
2. Install Jupyter Notebook or JupyterLab for local use:
   ```bash
   pip install notebook
   # or
   pip install jupyterlab
   ```
3. If using Google Colab, simply access [Google Colab](https://colab.research.google.com/) and upload the notebook.

## Data Requirements
- Geospatial data for California's road network, accessible through OpenStreetMap (OSM).
- Elevation data from the FABDEM dataset to create realistic 3D landscapes.

## Running the Notebook
1. If using Google Colab:
   - Open [Google Colab](https://colab.research.google.com/).
   - Upload the `3D_capri_google.ipynb` notebook.
   - Follow the instructions within the notebook to run the cells.
2. If running locally:
   - Open the terminal (or Command Prompt in Windows).
   - Navigate to the directory containing the notebook.
   - Run Jupyter Notebook or JupyterLab:
     ```bash
     jupyter notebook
     # or
     jupyter lab
     ```
   - Open the `3D_capri_google.ipynb` notebook in the Jupyter interface.
   - Run the cells in sequence, following any instructions provided within the notebook.

## Project Highlights
- Managed Copernicus 30m and FABDEM dataset ingestion using Azure Data Factory and Azure Lake, establishing efficient, scalable data processing workflows.
- Utilized Azure Databricks for transforming 2D road data into 3D by adding elevation, enhancing visual representation and analytical value.
- Developed Azure Functions to convert shapefile data to KML, enabling seamless 3D visualization integration with Google Earth.
- Output screenshots are included to illustrate the various stages of data processing and visualization.

## Output in 3D:
![White lines denote traffic congestion, Blue denotes road network](https://github.com/AnishmMore/3D-Visualization-of-California-s-Road-Network/blob/main/img1.jpeg)
![3D google earth view](https://github.com/AnishmMore/3D-Visualization-of-California-s-Road-Network/blob/main/img2.jpeg)
![Architecture](https://github.com/AnishmMore/3D-Visualization-of-California-s-Road-Network/blob/main/archi.jpeg)

## Attribution:
- This repository builds upon the work outlined in the paper Chen, Y.; Yang, X.; Yang, L.; Feng, J. An Automatic Approach to Extracting Large-Scale Three-Dimensional Road Networks Using Open-Source Data. Remote Sens. 2022, 14, 5746. https://doi.org/10.3390/rs14225746 and the associated repository [Road Elevation DSM GitHub](https://github.com/CubicsYang/Road_Elevation_DSM/).
- The code and methodology from the original project have been organized and extended in this repository. Full credit for the foundational work goes to the original authors. We encourage you to review the original work for further context and details.


## Contact Information
For any queries or support, please contact [![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anish-more99/)
