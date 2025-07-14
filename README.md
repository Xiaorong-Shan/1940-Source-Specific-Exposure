# Code and data for manuscript "Source-specific air pollution in areas and periods with limited data: application to 1940 in the United States"

Xiaorong Shan (单小容), Joan A. Casey, Jenni A. Shearston, Lucas R.F. Henneman

## Data used in this work

### 1. Sector-Specific Exposure at County-Level (1940 & 2010)

Estimated air pollution exposure by source sector for each U.S. county in the years 1940 and 2010. Metrics are based on emissions inventories, atmospheric modeling, and historical energy use data.

**Included Sectors and Pollutants:**

- **CMIP6 Modeled Pollutants:**
  - PM₂.₅ (Fine Particulate Matter)
  - O₃ (Ozone)

- **Mobile Source Exposure:**
  - Automobiles: Hydrocarbons (HC), Nitrogen Oxides (NOₓ), Carbon Monoxide (CO)

- **Stationary Source Exposure:**
  - Power plants
  - Oil & gas wells
  - Residential & commercial coal combustion

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

Processed data are organized by sector and year, and include metadata files describing variable definitions and data provenance.

> **Note:** If data download links or repository folders are available, include them here, e.g.:
>
> - [`/data/exposure_1940_2010/`](./data/exposure_1940_2010)
> - [`/data/epa_2010_monitors/`](./data/epa_2010_monitors)
> - [`/data/nhgis/`](./data/nhgis)

---

## Contact

For questions about the data or methodology, please contact Xiaorong Shan at xshan2@gmu.edu.

## Performing the analysis

First, download the data avilable on Zenodo. Save all files to ./data. Run the following scripts in order after changing the save_loc in each file:
