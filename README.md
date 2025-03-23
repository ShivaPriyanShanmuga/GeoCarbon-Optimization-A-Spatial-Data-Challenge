# GeoCarbon-Optimization-A-Spatial-Data-Challenge
## Overview
This project demonstrates geospatial data analysis and optimization using Python.
Given a set of land parcel polygons, the goal is to maximize the total carbon storage while adhering to budgetary and adjacency constraints. 

The project involves:

Geospatial Data Manipulation: Using GeoPandas for polygon data manipulation and spatial operations.

Coordinate System Management: Reprojecting polygon data for accurate area measurements.

Adjacency Calculation: Identifying adjacent polygons using edge-sharing criteria.

Optimization Modeling: Formulating and solving a Mixed Integer Linear Programming (MILP) problem using PuLP.

Visualization: Plotting the selected polygons and visualizing the results.

## Contents
- main.ipynb: The main Jupyter Notebook containing the code and analysis for the project.

## Installation
Follow these instructions to replicate the development environment:

1. Clone the repository:
   ```sh
   git clone https://github.com/ShivaPriyanShanmuga/GeoCarbon-Optimization-A-Spatial-Data-Challenge.git
   ```
2. Navigate to the project directory:
   ```sh
   cd GeoCarbon-Optimization-A-Spatial-Data-Challenge
   ```
3. Create a virtual environment:
   ```sh
   python -m venv env
   ```
4. Activate the virtual environment:
   
  . For Windows: 
   ```sh
   .\env\Scripts\activate
   ```
   
  . For macOS and Linux:
   ```sh
    source env/bin/activate
   ```
5. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
## Usage
To run the Jupyter Notebook and explore the geospatial data analysis and optimization, follow these steps:

1. Start Jupyter Notebook:
```sh
jupyter notebook
```
2. Open the main.ipynb notebook file.
3. Run the cells in the notebook to see the analysis and results.
