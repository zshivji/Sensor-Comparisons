# Sensor-Comparisons
GitHub repo for particulate matter (PM) sensor comparison project in Atlanta, GA. Code is either written for jupyer notebook (.ipynb).  
  
Zahra Shivji<sup>1</sup>, Sabrina Westgate<sup>1</sup>, and Nga Lee Ng<sup>1,2,3</sup>  
(1)School of Chemical & Biomolecular Engineering, Georgia Institute of Technology, Atlanta, GA  
(2)School of Earth and Atmospheric Sciences, Georgia Institute of Technology, Atlanta, GA  
(3)School of Civil and Environmental Engineering, Georgia Institute of Technology, Atlanta, GA  

## Outdoor Analysis
**Instruments**: Scanning Mobility Particle Sizer (SMPS), Aerosol Chemical Speciation Monitor (ACSM), QuantAQ MODULAIR-PM (MODPM)  
**Location**: Roof of Georgia Tech's Ford ES&T Building (Urban ATL)  
**Duration**: November 5, 2020 - January 1, 2021 (2 months, 26 days)  

### Analysis  
* **Timeseries_File_Generator.ipynb**: Cleans and combines raw data and exports to .csv for analysis and plotting  
* **Bias_Plots_File_Generator.ipynb**: Uses previous .csv to calaculate and export data for bias plots  
* **LOD.ipynb**: Calculates LOD (ug/m3) for the sensors in this environment  
* **Outdoor_Plots.ipynb**: Plots previously exported files for use in presenations/publications

## Indoor Analysis  
### Overview
**Instruments**: Scanning Mobility Particle Sizer (SMPS), QuantAQ MODULAIR-PM (MODPM)  
**Location**: Lecture Hall on Georgia Tech's Campus  
**Duration**: April 4, 2022 - April 8, 2022 (4 day, SMPS & MODPM); January 8, 2022 - April 8, 2022 (3 months, MODPM only)  

### Analysis
* **Timeseries_File_Generator.ipynb**: Cleans and combines raw data and exports to .csv for analysis and plotting  
* **Bias_Plots_File_Generator.ipynb**: Uses previous .csv to calaculate and export data for bias plots  
* **LOD.ipynb**: Calculates LOD (ug/m3) for the sensors in this environment  
* **Indoor_Plots.ipynb**: Plots previously exported files for use in presenations/publications


