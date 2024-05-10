# Overview
The purpose of this analysis was to use publically available data sources to identify US counties which would be good targets for a government program to address poor food accesss. I sought to identify communities that would be well served by such a program, and also estimate the health impact of these programs. 

## Data Sources

[CDC - 500 Cities Project](https://chronicdata.cdc.gov/500-Cities-Places/500-Cities-Census-Tract-level-Data-GIS-Friendly-Fo/k86t-wghb/about_data)
[FDA – Food Atlas](https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads/)

## Notes
- *food_access_analysis.ipynb* is my full analysis file and includes:
  -  Statement of assumptions
  - Data checks and EDA and summaries of findings
  - Descriptions of data challenges and merge-related considerations and choices
  - Additional plots and secondary analysis
  - Explanation of reasoning surrounding visualizations and analysis 
  - Regression analysis re: impact and assoicated results
- *food_access_analysis_key_viz_only.ipynb* is a "bare bones" version of the full *food_access_analysis.ipynb* which only includes data cleaning and the 3 key visualizations
- In order to create plots which are maps, you must down download and the load (In the "Mapping important variables" section) the US county-level shapefile, found here:  https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html