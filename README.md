# Maasai-Project
Use of GEE for class on remote sensing: Master Climate &amp; Society, Columbia University, instructor Pietro Ceccato

The goal of this project is to create: An easy interface to visualize product for climate, land cover, water bodies, trypanosomiasis fly data based first on Google Earth Egine and layering the disease data using Google Fusion Table. The final product will visualize the layers: precipitation temperature, vegetation, water bodies and high spatial images from LANDSAT.


Layers:
//be sure to add comments to cite the data sets within the application
1. MODIS Land Surface Temperature (LST)
The level-3 MODIS global Land Surface Temperature (LST) and Emissivity 8-day data are composed from the daily 1-kilometer LST product (MYD11A1) and stored on a 1-km Sinusoidal grid as the average values of clear-sky LSTs during an 8-day period.
MYD11A2.005 Land Surface Temperature and Emissivity 8-Day L3 Global 1km; 
Data availability (time {Jul 4, 2002 - Jan 3, 2017});
//Provider NASA LP DAAC at the USGS EROS Center
Tags ('modis', 'myd11a2', '8day', 'global', 'aqua', 'surface_temperature', 'emissivity', 'lst');
ImageCollection ID('MODIS/MYD11A2');
Please visit LP DAAC 'Citing Our Data' page for information on citing LP DAAC datasets.

2. CHIRPS: Climate Hazards Group InfraRed Precipitation with Station data (version 2.0 final)
Climate Hazards Group InfraRed Precipitation with Station data (CHIRPS) is a 30+ year quasi-global rainfall dataset. Spanning 50°S-50°N (and all longitudes), starting in 1981 to near-present, CHIRPS incorporates 0.05° resolution satellite imagery with in-situ station data to create gridded rainfall time series for trend analysis and seasonal drought monitoring. Each asset spans a pentad. Each of first 5 pentads in a month have 5 days. The last pentad contains all the days from the 26th to the end of the month.
The dataset contains one band: 'precipitation' (mm/pentad)
To cite this dataset, please use:
Funk, C.C., Peterson, P.J., Landsfeld, M.F., Pedreros, D.H., Verdin, J.P., Rowland, J.D., Romero, B.E., Husak, G.J., Michaelsen, J.C., and Verdin, A.P., 2014, A quasi-global precipitation time series for drought monitoring: U.S. Geological Survey Data Series 832, 4 p., http://dx.doi.org/10.3133/ds832
Data availability (time)
Jan 1, 1981 - Dec 27, 2016
Provider
UCSB/CHG
Tags
ucsb, chg, precipitation, climate, weather, geophysical
ImageCollection ID
UCSB-CHG/CHIRPS/PENTAD

3. MODIS Combined 16-Day NDVI
The Normalized Difference Vegetation Index is generated from the Near-IR and Red bands of each scene as (NIR - Red) / (NIR + Red), and ranges in value from -1.0 to 1.0. This product is generated from the MCD43A4 MODIS surface reflectance composites.
Data availability (time)
Feb 18, 2000 - Dec 26, 2016
Provider
Google
Tags
modis, mcd43a4, 16day, global, usgs, ndvi
ImageCollection ID
MODIS/MCD43A4_NDVI

4. Trypanosomiasis data 
Provider
University Nelson Mandela in Arusha, Tanazania. 
