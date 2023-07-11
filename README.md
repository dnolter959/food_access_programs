# n1_food_access
This is my analysis of low food access among the 65+ population in the US using publicly available data. Details of the analysis are available in n1_data_challenge.ipynb.

**Notes**
- *n1_data_challenge.ipynb* is my full analysis file and includes:
  -  Statement of assumptions
  - Data checks and EDA and summaries of findings
  - Descriptions of data challenges and merge-related considerations and choices
  - Additional plots and secondary analysis
  - Explanation of reasoning surrounding visualizations and analysis 
  - Regression analysis re: impact and assoicated results
- *key_visualizations_only.ipynb* is a "bare bones" version of the full *n1_data_challenge.ipynb* which only includes data cleaning and the 3 key visualizations
- In order to create plots which are maps, you must down download and the load (In the "Mapping important variables" section) the US county-level shapefile, found here:  https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html