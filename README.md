# Electric Vehicle Adoption and Charging Infrastructure in Washington State

Is Washington's public charging network keeping pace with EV growth, and how are income and rurality associated with where the gaps are largest?

**Live page:** https://sravyasss.github.io/Washington-State-EV-Analysis/

## Repo contents
- `index.html` consists of Homework 8 notebook that inlcudes (data sources, cleaning, exploration, and visualization brainstorm)
- `WA_EV_Project.zip` contains the datasets that we used for this project

## Data sources

- **WA Department of Licensing, EV Population Size History by County** (core dataset). Monthly EV registrations by county, split into battery EVs and plug-in hybrids. https://data.wa.gov/d/3d5d-sdqb
- **U.S. Department of Energy, Alternative Fuels Data Center, charging stations** (core dataset). Public Level 2 and DC fast charging ports, using December 31 snapshots from 2017 to 2025. https://afdc.energy.gov/data_download
- **U.S. Census Bureau, median household income (ACS B19013)**. 2020 to 2024 5-year estimates. https://data.census.gov/table/ACSDT5Y2024.B19013
- **U.S. Census Bureau, county population estimates**. 2017 to 2020 comes from the intercensal county file (CC-EST2020INT-ALLDATA), and 2020 to 2025 comes from the Census population estimates datasets.
  - 2010 to 2020 intercensal: https://www.census.gov/data/tables/time-series/demo/popest/intercensal-2010-2020-counties-detail.html
  - 2020 to 2025: https://www2.census.gov/programs-surveys/popest/datasets/
  - File layout for the year codes: https://www2.census.gov/programs-surveys/popest/technical-documentation/file-layouts/2010-2020/intercensal/county/CC-EST2020INT-ALLDATA.pdf
- **U.S. Census Bureau, Washington county boundaries** (Cartographic Boundary File). Used for maps and to place each charging station in a county. https://www.census.gov/geographies/mapping-files/time-series/geo/cartographic-boundary.html
- **USDA, Rural-Urban Continuum Codes (2023)**. Sorts counties into metro and nonmetro. https://www.ers.usda.gov/data-products/rural-urban-continuum-codes
- **WA Department of Licensing, EV Population Data** (optional). One row for every EV currently registered, used for brands and vehicle types. https://data.wa.gov/d/f6w7-q2d2

## Group members
Anushka Maddisetty, Hamda Hassan, Hemant Arulijothi, Sravya Murala
