# Maasai-Project
Use of GEE for class on remote sensing: Master Climate &amp; Society, Columbia University, instructor Pietro Ceccato


0. Layers:
1. MODIS Land Surface Temperature (LST)
Import
The level-3 MODIS global Land Surface Temperature (LST) and Emissivity 8-day data are composed from the daily 1-kilometer LST product (MYD11A1) and stored on a 1-km Sinusoidal grid as the average values of clear-sky LSTs during an 8-day period.

MYD11A2.005 Land Surface Temperature and Emissivity 8-Day L3 Global 1km; 
Data availability (time {Jul 4, 2002 - Jan 3, 2017});
//Provider NASA LP DAAC at the USGS EROS Center
Tags ('modis', 'myd11a2', '8day', 'global', 'aqua', 'surface_temperature', 'emissivity', 'lst');
ImageCollection ID('MODIS/MYD11A2');


MYD11A2 is comprised of the following layers for daytime and nighttime observations:
LST_Day_1km: Daytime Land Surface Temperatures (K), Scale 0.02
QC_Day: Daytime Surface Temperature quality control assessments, see QC bit flags
Day_view_time: Daytime LST Observation Times (Hours), Scale 0.1
Day_view_angl: Daytime View Zenith Angles (Degrees), Offset -65.0
LST_Night_1km: Nighttime Land Surface Temperatures (K), Scale 0.02
QC_Night: Nighttime Surface Temperature quality control assessments, see QC bit flags
Night_view_time: Nighttime LST Observation Times (Hours), Scale 0.1
Night_view_angl: Nighttime View Zenith Angles (Degrees), Offset -65.0
Emis_31: Bands 31 Emissivity, Scale 0.002, Offset 0.49
Emis_32: Bands 32 Emissivity, Scale 0.002, Offset 0.49
Clear_sky_days: Clear Sky Day Coverage, see Clear Sky Flags.
Clear_sky_nights: Clear Sky Nighttime Coverage, see Clear Sky Flags.
QC bit flags:

Bits 0-1: Mandatory QC Flag
00: LST produced, good quality, not necessary to examine detailed QC.
01: LST produced, unreliable or unquantifiable quality, recommend examination of more detailed QC.
10: LST not produced due to cloud effects.
11: LST not produced primarily due to reasons other than clouds.
Bits 2-3: Data Quality Flag
00: Good quality L1B in bands 31 and 32.
01: Other quality data.
10: TBD
11: TBD
Bits 4-5: Emissivity Error Flag
00: Average emissivity error ≤ 0.01
01: Average emissivity error ≤ 0.02
10: Average emissivity error ≤ 0.04
11: Average emissivity error > 0.04
Bits 6-7: LST Error Flag
00: Average LST error ≤ 1 K
01: Average LST error ≤ 2 K
10: Average LST error ≤ 3 K
11: Average LST error > 3 K
Clear Sky Flags:

Clear Sky Flag for each day (bit 0 is day 1, bit 1 is day 2, etc):
0: Day/Night is not clear-sky.
1: Day/Night is clear-sky.
Version-5 MODIS/Aqua Land Surface Temperature/Emissivity products are Validated Stage 2, meaning that accuracy has been assessed over a widely distributed set of locations and time periods via several ground-truth and validation efforts. Although there may be later improved versions, these data are ready for use in scientific publications.

Please visit LP DAAC 'Citing Our Data' page for information on citing LP DAAC datasets.

2. CHIRPS: Climate Hazards Group InfraRed Precipitation with Station data (version 2.0 final)

Data availability (time)
Jan 1, 1981 - Dec 27, 2016
Provider
UCSB/CHG
Tags
ucsb, chg, precipitation, climate, weather, geophysical
ImageCollection ID
UCSB-CHG/CHIRPS/PENTAD
Import
Climate Hazards Group InfraRed Precipitation with Station data (CHIRPS) is a 30+ year quasi-global rainfall dataset. Spanning 50°S-50°N (and all longitudes), starting in 1981 to near-present, CHIRPS incorporates 0.05° resolution satellite imagery with in-situ station data to create gridded rainfall time series for trend analysis and seasonal drought monitoring.

Each asset spans a pentad. Each of first 5 pentads in a month have 5 days. The last pentad contains all the days from the 26th to the end of the month.

The dataset contains one band: 'precipitation' (mm/pentad)

To cite this dataset, please use:

Funk, C.C., Peterson, P.J., Landsfeld, M.F., Pedreros, D.H., Verdin, J.P., Rowland, J.D., Romero, B.E., Husak, G.J., Michaelsen, J.C., and Verdin, A.P., 2014, A quasi-global precipitation time series for drought monitoring: U.S. Geological Survey Data Series 832, 4 p., http://dx.doi.org/10.3133/ds832
