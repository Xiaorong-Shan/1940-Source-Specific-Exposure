# Code and data for manuscript "Source-specific air pollution in areas and periods with limited data: application to 1940 in the United States"

Xiaorong Shan (单小容), Joan A. Casey, Jenni A. Shearston, Lucas R.F. Henneman

## Data used in this work

## 1. Sector-Specific County-Level Exposure (1940 & 2010)

Estimated air-pollution exposure by source sector for each U.S. county in 1940 and 2010. Metrics are based on emissions inventories, atmospheric modeling, and historical energy-use data.

### Included Sectors & Pollutants

#### A. CMIP6-Modeled Pollutants
- **PM₂.₅ (Fine Particulate Matter)**  
  11 global climate models  
- **O₃ (Ozone)**  
  6 global climate models  

#### B. Mobile Source Emissions (Automobiles)
Population-weighted emissions of:
- **HC** (Hydrocarbons)  
- **NOₓ** (Nitrogen Oxides)  
- **CO** (Carbon Monoxide)  

#### C. Stationary Source Emissions

(1). **Power Plants**  
   - **Fuel Types:** Coal, Gas, Petroleum, Renewable  
   - **Spatial Models:** HYADS, Inverse Distance Weighting (IDW)  

(2). **Wells**  
   - **Production Types:** Oil, Gas  
   - **Spatial Interpolation:** IDW  

(3). **Residential & Commercial Combustion**  
   - **Fuel:** Coal  
   - **Pollutants:** BC, CO, NH₃, NMVOC, NOₓ, OC, SO₂  
   - **Exposure Metric:** Heating Degree Days (HDD)  

---

### 2. 1940 Visibility Estimates

Observed or reconstructed visibility data from 1940, used as a proxy for historical particulate matter concentrations.

---

### 3. 2010 EPA Monitor-Based Emission Measurements

County-level ambient pollutant concentrations measured by EPA monitoring networks in 2010, used for model validation and calibration.

---

### 4. Population and Geographic Data

Population and geographic boundary data were obtained from the [National Historical Geographic Information System (NHGIS)](https://www.nhgis.org/), enabling population-weighted exposure estimates and standardized spatial referencing.

---

## Data Access

The data is available here: https://zenodo.org/records/16329316 


---

## Contact

For questions about the data or methodology, please contact Xiaorong Shan at xshan2@gmu.edu.

## Performing the analysis

First, download the data avilable on Zenodo. Save all files to ./data. Run the following scripts in order after changing the save_loc in each file:
