# ERA5_hourly_data_request
Python code to download ERA5 hourly data from climate.copernicus.eu website.

The Python code will help users download the ERA5 hourly data on single levels from 1940 to the present for various variables. The climate data store user forum suggested downloading the hourly data for longer months in a single query is not feasible, so this code downloads the two months of data to a single NetCDF file for the duration.
You'll need to manually provide the required variables in the variable section because this code is developed for surface 10m u- and v-components only. However, users can get a chance to provide variables of interest at the time of running code in the later updates. 

Preliminary requirements are users must install the cdsapi package through the conda environment or pip management system. 
