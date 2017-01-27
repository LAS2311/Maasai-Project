# Maasai-Project
Use of GEE for class on remote sensing: Master Climate &amp; Society, Columbia University, instructor Pietro Ceccato


Layers:
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
