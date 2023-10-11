# ERA5_hourly_data_request
Python code to download ERA5 hourly data from climate.copernicus.eu website.

The Python code will help users download the ERA5 hourly data on single levels from 1940 to the present for various variables. The climate data store user forum suggested downloading the hourly data for longer months in a single query is not feasible. Therefore, the present code downloads the two months' data into a single NetCDF file for the duration period.
You must manually provide the required variables in the variable section because this code is only developed for surface 10m u- and v-components. However, users can get a chance to provide variables of interest at the time of running code in the later updates. 
While running this code, it will prompt you to provide the start and end year, so users should give it in the YYYY format. After that, python code will take care of the downloading process.

Preliminary requirements are users must install the cdsapi package through the conda environment or pip management system. 
