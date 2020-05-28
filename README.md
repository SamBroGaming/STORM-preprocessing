# STORM-preprocessing
These are the scripts to conduct the data-preprocessing for the STORM model. Input data is taken from IBTrACS, see https://www.ncdc.noaa.gov/ibtracs/. 
Please reach out if you have any questions!

Please run the scripts as follows:

1. preprocessing.py (this is a module)
2. coefficients.py  (this is a module)
3. environmental.py (this is a module)
4. Make_land_ocean_mask.py <-- in Python 2.7 (uses Basemap), this file stores a .txt file that can be loaded in Python 3.x
5. genesis_matrix.py  (this is a module)
6. master_preprocessing.py  (this is the master script using the other modules)
