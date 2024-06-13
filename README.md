# Additional metadata information concerning NIVA FerryBox systems 

## 1. Method description for measured variables 

Sensors were equipped on an underway flow-through system (FerryBox) on ships of opportunity. Clean seawater inlets were custom installed at ∼5 m depth and directly pumped to a sensor package.  

### Sea Water Temperature (unit: 'degree_Celsius' ) 

A SeaBird digital oceanographic thermometer (SBE38) was installed at the FerryBox inlet, in addition to a SeaBird SBE45 thermosalinograph in the FerryBox cabinet. The temperature sensors were periodically checked and calibrated using a traceable reference thermometer.  

<ins>QC tests applied</ins>: Water flow test, GPS quality test, Frozen test, Range test, Spike test
 
### Sea Water Salinity (unit: 'PSU' ) 

A SeaBird thermosalinograph (SBE45) was installed in the FerryBox cabinet. The salinity sensor was periodically checked and calibrated using discrete salinity samples measured using a laboratory salinometer (Portasal). 

<ins>QC tests applied</ins>: Water flow test, GPS quality test, Frozen test, Range test, Spike test

### Sea Water Oxygen Saturation (unit: ‘%’) 

Measured with oxygen optode (Aanderaa optode 4835), which was periodically checked and calibrated with discrete samples analyzed using Winkler titration.  

<ins>QC tests applied</ins>: Water flow test, GPS quality test, Frozen test,  Range test
 
### Chlorophyll a fluorescence (mg/m3) 

A Turner Designs C3 submersible sensor configured with chlorophyll a, coloured dissolved organic matter (CDOM), and turbidity sensors; excitation 465 nm, emission 696 nm; calibrated using algal cultures, and periodically validated with Turner Designs solid secondary standards and Chl-a samples analysed via methanol extraction and spectrophotometry. 

<ins>QC tests applied</ins>: Water flow test, GPS quality test, Frozen test, Range test

### Coloured dissolved organic matter (CDOM) fluorescence (mg/m3) 

A Turner Designs C3 submersible sensor configured with chlorophyll a, coloured dissolved organic matter (CDOM), and turbidity sensors; excitation 325 nm, emission 470 nm; calibrated using quinine sulfate and periodically validated using Turner Designs solid secondary standards. 

<ins>QC tests applied</ins>:  Water flow test, GPS quality test, Frozen test

### Turbidity (Formazin Nephelometric Unit, FNU) 

A Turner Designs C3 submersible sensor configured with chlorophyll a, coloured dissolved organic matter (CDOM), and turbidity sensors; excitation and emission at 850 nm; calibrated using formazin calibration solutions and periodically validated with a custom-made solid standard (NIVA). 

<ins>QC tests applied</ins>:  Water flow test, GPS quality test, Frozen test
 
## 2. Calibration procedure 

 
Master calibration and solid cal (sensor adjustment) 

## 3. Quality control procedure 

Quality control procedures follow established protocols [1, 2].  

 

The following tests have been implemented in [1, 2] for the real-time quality control:  

1. **Water flow test** It checks if water pump operates and if the difference between temperature measured in the cabinet and at inlet is within acceptable range.  

2. **GPS quality test** Bounded variance test and range test are applied to boat velocity calculated using finite difference and longitude and latitude measurements and including earth curvature.  

3. **Frozen test** It checks if 4 consecutive values before the tested value are equal.  

4. **Range test** It checks that data is within a specified range of values. Accepts time range and geographic range. The latter is based on minimum and maximum latitudes and longitudes values.  

5. **Spike test** Tests the difference between sequential measurements as defined in [2].  

Outcomes of the above tests, per parameter, per timestamp are combined into the final quality control flag. The result is passed if at least one test passed, and no tests failed. The result is failed if at least one test failed. Tests 1 and 2 are mandatory for all parameters. Tests 3-5 are by default applied but also configurable in [2].  

 

## References: 

[1] EuroGOOS Data Management, Exchange, and Quality Working Group (2015). **Real Time Quality Control of biogeochemical measurements.** https://eurogoos.eu/download/RTQC_BGC_recommendations_v2.5.pdf 

[2] Copernicus Marine in situ TAC BGC quality control group (2022). **Real time quality control of biogeochemical measurements within Copernicus Marine in situ TAC.** https://doi.org/10.13155/75704 

 

 
