## Team Name: 
- WangWangCheChen

## Team Members: 
- Xiyu Wang, Ivy Wang, Emily Chen, Tracy Che

## Research Scope

- **Study Area:** North America (USA, Canada, Mexico) and South America
- **Trade Focus:** Solar photovoltaic (PV) exports from China to countries in the study area only
- **Primary Datasets Used:** Ember China Solar PV Export dataset and IRENA installed capacity data
- **Field of Study:** China's solar PV exports and installed solar PV capacity in the study countries

## Main Research Question

- How have China's solar PV exports to North and South American countries evolved over time?
- How do these trends relate to changes in installed solar PV capacity in these countries?

## Supporting Questions

- How do differences in solar PV import tariffs and trade policies across countries in the study area relate to Chinese solar PV export trends?
- How have changes in solar PV import tariffs and trade restrictions coincided with changes in installed solar PV capacity in selected countries?
- How might differences in national renewable energy policies and incentives help explain variations in solar PV capacity growth across the study area?

## Intended Audience

- This project is intended for policymakers, energy researchers, solar industry stakeholders, and students interested in how China's solar PV exports relate to solar energy growth in North and South America.

## Dictionary
- **File:** CLEANED_Study_area_data_2018_2025.csv
- **Unit of observation:** Each row in CLEANED_Study_area_data_2018_2025.csv represents one country in one year, for 15 countries and the years 2018 to 2025. For the list of country see Coverage Selection below
- **Coverage:** North America — Canada, Mexico, United States; South America — Argentina, Bolivia, Brazil, Chile, Colombia, Ecuador, Guyana, Paraguay, Peru, Suriname, Uruguay, Venezuela.)
- **Size:** 120 rows × 12 columns
- **Data Sources:**
  - Ember – China Cleantech Export Data*
    - https://ember-energy.org/data/china-cleantech-export-data/
  - Ember – China's Solar PV Exports*
    - https://ember-energy.org/data/china-solar-exports-data/
  - IRENASTAT – Electricity Capacity and Generation
    - https://pxweb.irena.org/
  - World Bank – Population, total
    - https://data.worldbank.org/indicator/SP.POP.TOTL
  - *: For Ember China Cleantech Export and China's Solar PV Exports Data, Ember presents data from the General Administration of Customs of the People’s Republic of China (GACC). Prior to 2022, assembled and non-assembled cells are not disaggregated into separate commodity codes in GACC reporting. The commodity code used is 85414020 (Solar cells). All exports in this category are assigned to panel exports. From 2022 onwards, the commodity code used is 85414300 (Photovoltaic cells assembled in modules or made up into panels).

- **Variable dictionary:**
  - **Area：**
    - **Definition:** Country name
    - **Unit:** Character
    - **Source:** Across four datasets
    - **Definition in the source documentation:** Country name
  - **Study_scope**
    - **Definition:** Country name
    - **Unit:** Character
    - **Source:** Self-classification
    - **Definition in the source documentation:** North America or South America
  -  **Year**
    - **Definition:** Observation year
    - **Unit:** Year
    - **Source:** Across four datasets
    - **Definition in the source documentation:** Observation year
  -  **China_panel_exports_USD**
    - **Definition:** China annual solar panel export value
    - **Unit:** USD
    - **Source:** China's Solar PV Exports, Ember
    - **Definition in the source documentation:** Sourced to Column *Export amount in US dollars*, defined and explained as, "Average monthly panel prices are sourced from weekly InfoLink Consulting Group publications. Prices are reported in USD/W. The market share is based on annual
shares reported by the IEA and InfoLink. The annual share is scaled to estimated monthly market shares, used to weight the type and calculate an average monthly price."
  -  **China_panel_exports_MW**
    - **Definition:** China annual solar panel export capacity
    - **Unit:** MW
    - **Source:** China's Solar PV Exports, Ember
    - **Definition in the source documentation:** The capacity (MW) of solar export products is not reported by GACC. Ember estimates it for panels by dividing the export value in US dollars (from the raw GACC customs data) by the average monthly panel price.
 -  **CleanTech_solarPV_USD**
    - **Definition:** China annual solar PV export value
    - **Unit:** USD
    - **Source:** China Cleantech Export Data, Ember
    - **Definition in the source documentation:** Prior to 2022, only assembled and non-assembled cells data are included in the Solar PV category. From 2022 onwards, Solar PV category includes solar cell, solar modules, solar wafters, where Solar cell is defined as Photovoltaic
cells assembled in modules or made up into panels. Solar modules figures include the original pre-2022 Solar PV data plus Photovoltaic cells not assembled in modules or made up into panels.
 -  **CleanTech_alltech_USD**
    - **Definition:** China annual cleantech export value
    - **Unit:** USD
    - **Source:** China Cleantech Export Data, Ember
    - **Definition in the source documentation:** Not defined
 -  **PV_installed_capacity_MW**
    - **Definition:** Total installed solar PV capacity
    - **Unit:** MW
    - **Source:** Electricity Capacity and Generation, IRENASTAT
    - **Definition in the source documentation:** Sourced to variable *Electrical Installed Capacity*. The power capacity data shown in these tables represents the maximum net generating capacity of power plants and other installations used to produce electricity. For most countries and technologies, the data reflects the capacity installed and connected at the end of the calendar year.
 -  **PV_generation_GWh**
    - **Definition:** Annual solar PV electricity generation
    - **Unit:** GWh
    - **Source:** Electricity Capacity and Generation, IRENASTAT
    - **Definition in the source documentation:** Sourced to variable *Electricity Generation (GWh)*. Electricity generation (GWh) is the gross electricity produced by electricity plants, combined heat and power plants (CHP) and distributed generators measured at the output terminals of generation. It includes on-grid and off-grid generation, and it also includes the electricity self-consumed in energy industries; not only the electricity fed into the grid (net electricity production).
 -  **Population**
    - **Definition:** Total population
    - **Unit:** Count
    - **Source:** Population, total, World Bank
    - **Definition in the source documentation:** Total population is based on the de facto definition of population, which counts all residents regardless of legal status or citizenship. The values shown are midyear estimates.
 -  **PV_capacity_additions_MW**
    - **Definition:** Annual net change in installed PV capacity
    - **Unit:** MW
    - **Source:** Electricity Capacity and Generation, IRENASTAT
    - **Definition in the source documentation:** Further processed from Electrical Installed Capacity figures. Calculated by current year’s electrical installed capacity minus previous year’s electrical installed capacity.
 -  **PV_installed_W_per_person**
    - **Definition:** Installed PV capacity per person
    - **Unit:** W/person
    - **Source:** Electricity Capacity and Generation, IRENASTAT, and Population, total, World Bank
    - **Definition in the source documentation:** Further processed from Electrical Installed Capacity figures and total population. Calculated by electrical installed capacity divided by the corresponding year’s population. 
