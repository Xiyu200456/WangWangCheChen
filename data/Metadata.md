# Dataset Metadata
## Dataset 1: Ember China Solar PV Export

### Data Access

- **Source:** Ember
- **Dataset:** China's Solar PV Exports
- **Official Website:** https://ember-energy.org/data/china-solar-exports-data/
- **File Name:** `mart_solar_exports_full_release_monthly.csv`
- **Format:** CSV
- **Update Frequency:** Monthly

### Expected Variables
The dataset contains 31,254 observations and 13 variables, including:

- **Geographic Information:** `Area`, `Area type`, and `Region`, identifying destination countries, economies, and geographic regions.
- **Temporal Information:** `Date`, indicating the monthly reporting period.
- **Commodity Information:** `Commodity code` and `Commodity type`, identifying solar PV product categories, including panels, cells, and wafers.
- **Export Volume and Value:** `Amount (items)`, `Amount (kg)`, and `Amount (USD)`, representing the quantity, weight, and monetary value of exported products.
- **Commodity Price:** `Commodity price` and `Price unit`, indicating the reported product price and its unit.
- **Export Capacity:** `Capacity (MW)` and `Cumulative capacity (MW)`, representing estimated export capacity and cumulative estimated export capacity.

### Spatial and Temporal Coverage

- **Spatial Coverage:** Global, including 244 unique geographic areas or aggregates. The dataset covers Africa, Europe, Asia, Latin America and the Caribbean, North America, the Middle East, and Oceania.
- **Project Study Area:** North America (United States, Canada, and Mexico) and South America.
- **Temporal Coverage:** January 2017 – August 2026 in the current downloaded dataset.
- **Temporal Resolution:** Monthly.
- **Commodity Types:** Panels, cells, and wafers.

### Permissions and Restrictions

Ember provides publicly accessible data under the Creative Commons Attribution 4.0 (CC BY 4.0) license. Reuse and adaptation are permitted with appropriate attribution.

**Data Limitations:**

- The dataset includes country-level observations and regional aggregates, which should be distinguished during analysis.
- Some regional classification values are missing, particularly in records representing regional aggregates.
- Export capacity values are estimated and do not directly represent installed solar PV capacity.
- Reported export destinations may not always be the final destination of the products.
- Data coverage differs across commodity types, and 2026 is currently an incomplete year.


## Dataset 2: IRENA Solar PV Installed Capacity
### Data Access

- **Source:** International Renewable Energy Agency (IRENA)
- **Dataset:** IRENA Renewable Energy Statistics
- **Official Website:** https://pxweb.irena.org/pxweb/en/IRENASTAT/IRENASTAT__Power%20Capacity%20and%20Generation/Country_ELECSTAT_2026_H2_PX.px/
- **File Name:** `IRENA.xlsx`
- **Format:** Excel (.xlsx)
- **Worksheet:** ELEC-C

### Expected Variables

The dataset contains 21,504 observations and 6 variables:

- **Geographic Information:** `Country/area`, identifying countries or geographic areas.
- **Technology:** `Technology`, identifying solar photovoltaic and solar thermal energy.
- **Data Type:** `Data Type`, distinguishing electricity generation (GWh) and electrical installed capacity (MW).
- **Grid Connection:** `Grid connection`, identifying grid connection categories.
- **Temporal Information:** `Year`, representing the reporting year.
- **Capacity and Generation:** `Value`, representing the corresponding installed capacity or electricity generation measurement.

### Spatial and Temporal Coverage

- **Spatial Coverage:** Global, with 224 unique countries or areas represented in the downloaded file.
- **Project Study Area:** North America (United States, Canada, and Mexico) and South America.
- **Temporal Coverage:** 2018–2025.
- **Temporal Resolution:** Annual.
- **Technology Coverage:** Solar photovoltaic and solar thermal energy.

### Permissions and Restrictions

The dataset is publicly accessible through IRENASTAT. Users should follow IRENA's official terms and conditions and provide appropriate source attribution.

**Data Limitations:**

- The `Value` column contains 12,583 missing observations.
- The original Excel file uses grouped labels, resulting in missing entries in some categorical columns during import.
- Installed capacity and electricity generation have different units (MW and GWh) and should not be directly compared.
- The dataset provides annual observations, while the Ember export dataset provides monthly observations. Temporal alignment will be necessary for further analysis.


## Dataset 3: World Bank Population Dataset

### Data Access

- **Source:** World Bank Group
- **Dataset:** World Total Population Prospects
- **Official Website:** https://data.worldbank.org/indicator/SP.POP.TOTL
- **File Name:** `712population_712API_SP.POP.TOTL_DS2_en_csv_v2_5254.xlsx`
- **Format:** xlsx
- **Update Frequency:** Yearly

### Expected Variables
The dataset contains 2,120 observations, including:

- **Geographic Information:** `Country Name`, `Country Code`, and `Region`, identifying countries and corresponding codes.
- **Data Attribution:** `Indicator Name`, `Indicator Code`,
- **Temporal Information:** `2018`, `2019`, `2020`, `2021`, `2022`, `2023`, `2024`, `2025`, indicating the yearly reporting period.

### Spatial and Temporal Coverage

- **Spatial Coverage:** Global, including 266 unique geographic areas or aggregates. The dataset covers Africa, Europe, Asia, Latin America and the Caribbean, North America, the Middle East, and Oceania.
- **Project Study Area:** North America (United States, Canada, and Mexico) and South America.
- **Temporal Coverage:** 2018 – 2025 in the current downloaded dataset.
- **Temporal Resolution:** Yearly.

### Permissions and Restrictions

World Bank provides publicly accessible data under the Creative Commons Attribution 4.0 (CC BY 4.0) license. Reuse and adaptation are permitted with appropriate attribution.

**Data Limitations:**

- A common limitation of population data is that the figures presented are estimates rather than exact counts. The World Bank notes that current population estimates for developing countries often lack (i)reliable, recent census data and (ii) pre- and post-census estimates for countries with census data, which are provided by the United Nations Population Division and other external agencies. Moreover, the cohortcomponent method used in the dataset is a standard approach to estimating and projecting population size that requires data on fertility, mortality, and net migration. These data are often collected through sample surveys, which may have small sample sizes or limited geographic coverage. Consequently,population estimates derived from demographic models are susceptible to biases and errors arising from limitations in both the models and the underlying data. 


## Dataset 4: Ember Clean Tech Export Monthly in study areas

### Data Access

- **Source:** Ember
- **Dataset:** China Clean Tech Export Data
- **Official Website:** https://ember-energy.org/data/china-solar-exports-data/
- **File Name:** `712clean_tech_exports_full_release_monthly.csv`
- **Format:** CSV
- **Update Frequency:** Monthly

- ### Expected Variables
The dataset contains 31,254 observations and 13 variables, including:

- **Geographic Information:** `Area`, `Area type`, and `Region`, identifying destination countries, economies, and geographic regions.
- **Temporal Information:** `Date`, indicating the monthly reporting period.
- **Commodity Information:** `Commodity category`, distinguishing between All Technologies and Solar Panel products.
- **Export Volume and Value:** `Amount (USD)`, representing the monetary value of exported products.
- **Rolling Export Value:** Amount 12 month rolling sum (USD), representing the cumulative export value over the preceding twelve months, including the current month.

### Spatial and Temporal Coverage

- **Spatial Coverage:** Contains 54 unique geographic areas, including countries and territories across North America, Central America, South America, and the Caribbean. The geographic regions are categorized as North America and Latin America and the Caribbean.
- **Project Study Area:** North America (United States, Canada, and Mexico) and South America.
- **Temporal Coverage:** January 2018 – August 2026 in the current downloaded dataset.
- **Temporal Resolution:** Monthly.
- **Commodity Types:** All technologies and Solar PV

### Permissions and Restrictions

Ember provides publicly accessible data under the Creative Commons Attribution 4.0 (CC BY 4.0) license. Reuse and adaptation are permitted with appropriate attribution.

**Data Limitations:**

- The Amount 12 month rolling sum (USD) column contains 628 missing values in each worksheet, particularly where a complete twelve-month reporting history is unavailable.
- Reported export destinations may not always represent the final installation destinations of clean technologies, as products may be redistributed or re-exported through intermediary countries.
- The All technologies category includes Solar PV exports, so the two categories should not be added together to calculate total clean technology exports.
- The dataset provides monthly observations, while the IRENA installed capacity and World Bank population datasets provide annual observations. Temporal aggregation and alignment will therefore be necessary for further analysis.
- 2026 is an incomplete reporting year.

