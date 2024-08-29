## Python Foundation for Spatial Analysis - Class Project

This repository contains a Jupyter Notebook developed as part of the "Python Foundation for Spatial Analysis" course, offered by [Spatial Thoughts](https://spatialthoughts.com) in July 2024. The course was instructed by Ujaval Ganghi, with Vigna Purohit serving as the Training Associate.

### Project Overview

The objective of this project is to perform spatial analysis on the distribution of Galagos (a type of primate) in relation to protected areas in Tanzania and Malawi. The analysis utilizes Python's powerful geospatial libraries, such as `pandas` and `geopandas`, to read and process spatial data, perform spatial joins, and export the results for further use.

### Data Sources

- **Galagos Point Locations**: A dataset containing the geographic coordinates of Galagos observations in Tanzania and Malawi, provided in an Excel format.
- **Protected Areas**: A shapefile dataset from the World Database on Protected Areas (WDPA) for August 2024, representing protected areas in the study region.

### Project Workflow

1. **Data Import**: Reading point data from an Excel file and protected area data from a shapefile.
2. **Geospatial Data Creation**: Converting the Galagos point data into a GeoDataFrame with a specified coordinate reference system (CRS).
3. **Spatial Join**: Performing a spatial join to determine which Galagos observations intersect with protected areas.
4. **Export Results**: Saving the spatial join results to a GeoPackage file for further analysis.

### Key Technologies

- **Python**: The primary programming language used for the analysis.
- **pandas**: Used for data manipulation and analysis.
- **geopandas**: Extended the capabilities of pandas to allow for spatial operations on geometric types.
- **Jupyter Notebook**: Used to write, document, and execute the code interactively.

### How to Use

To run the notebook, clone this repository and open `galagos_project.ipynb` in Jupyter Lab or Jupyter Notebook. Make sure to have the required Python packages installed, including `pandas`, `geopandas`, and others listed in the `requirements.txt` (if provided).

### Conclusion

This project demonstrates how to combine and analyze spatial datasets using Python, focusing on practical applications in environmental and ecological studies. The resulting workflow can be adapted to similar geospatial analysis projects.

### Acknowledgments

This project was completed as part of the Python Foundation for Spatial Analysis course offered by Spatial Thoughts. Special thanks to the instructor Ujaval Ganghi and the Training Associate Vigna Purohit for their guidance and support.

