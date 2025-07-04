
# Data Product Canvas - Berlin Building Industry yearly (source-aligned)

## Metadata

* owner: Open Data Product
* description: Source-aligned data product providing Berlin building industry data
* updated: 2025-07-29

## Input Ports

### Baugewerbe in Berlin 2020

* owner: Amt für Statistik Berlin-Brandenburg
* url: https://www.statistik-berlin-brandenburg.de/e-ii-2-e-iii-2-j
* license: CC-BY-3.0-Namensnennung
* updated: 2022-02-12

**Files**

* [SB_E02-02-00_2020j01_BE.xlsx](https://download.statistik-berlin-brandenburg.de/7910f648886e1337/913cbcf0e17e/SB_E02-02-00_2020j01_BE.xlsx)

### Baugewerbe in Berlin 2021

* owner: Amt für Statistik Berlin-Brandenburg
* url: https://www.statistik-berlin-brandenburg.de/e-ii-2-e-iii-2-j
* license: CC-BY-3.0-Namensnennung
* updated: 2022-02-01

**Files**

* [SB_E02-02-00_2021j01_BE.xlsx](https://download.statistik-berlin-brandenburg.de/bcbf8552c422eb64/d3d555404d57/SB_E02-02-00_2021j01_BE.xlsx)

### Baugewerbe in Berlin 2022

* owner: Amt für Statistik Berlin-Brandenburg
* url: https://www.statistik-berlin-brandenburg.de/e-ii-2-e-iii-2-j
* license: CC-BY-3.0-Namensnennung
* updated: 2023-02-01

**Files**

* [SB_E02-02-00_2022j01_BE.xlsx](https://download.statistik-berlin-brandenburg.de/ef6cb735b329cbb4/ee8677b51646/SB_E02-02-00_2022j01_BE.xlsx)

### Baugewerbe in Berlin 2023

* owner: Amt für Statistik Berlin-Brandenburg
* url: https://www.statistik-berlin-brandenburg.de/e-ii-2-e-iii-2-j
* license: CC-BY-3.0-Namensnennung
* updated: 2024-02-29

**Files**

* [SB_E02-02-00_2023j01_BE.xlsx](https://download.statistik-berlin-brandenburg.de/3afd71d2f9813ad7/d5c9c0bbe8ab/SB_E02-02-00_2023j01_BE.xlsx)

## Transformation Steps

* [Data extractor](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/extract/data_extractor.py) extracts data from inout ports
* [Data copier](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_copier.py) copies and renames extracted data
* [Data CSV converter](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_csv_converter.py) converts Excel files to CSV format
* [Data CSV aggregator](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_csv_aggregator.py) aggregates data to be used as output ports

## Output Ports

### Berlin Building Industry 2020 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/tree/main/data/02-silver/berlin-building-industry-2020-00
* updated: 2025-07-29

**Files**

* [berlin-building-industry-2020-00-1-companies-employees-and-working-hours.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-1-companies-employees-and-working-hours.csv)
* [berlin-building-industry-2020-00-10-key-figures-second-quarter-by-sectors.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-10-key-figures-second-quarter-by-sectors.csv)
* [berlin-building-industry-2020-00-11-working-hours-second-quarter-by-sectors-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-11-working-hours-second-quarter-by-sectors-and-employee-size-categories.csv)
* [berlin-building-industry-2020-00-12-turnover-second-quarter-by-sectors-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-12-turnover-second-quarter-by-sectors-and-employee-size-categories.csv)
* [berlin-building-industry-2020-00-13-turnover-in-2019-by-sector-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-13-turnover-in-2019-by-sector-and-employee-size-categories.csv)
* [berlin-building-industry-2020-00-14-legal-entities-employees-turnover-and-investments-extension-building-industry.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-14-legal-entities-employees-turnover-and-investments-extension-building-industry.csv)
* [berlin-building-industry-2020-00-14-legal-entities-employees-turnover-and-investments-main-building-industry.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-14-legal-entities-employees-turnover-and-investments-main-building-industry.csv)
* [berlin-building-industry-2020-00-2-key-figures-by-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-2-key-figures-by-employee-size-categories.csv)
* [berlin-building-industry-2020-00-3-companies-employees-salaries-by-sectors.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-3-companies-employees-salaries-by-sectors.csv)
* [berlin-building-industry-2020-00-4-employees-by-position.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-4-employees-by-position.csv)
* [berlin-building-industry-2020-00-5-working-hours-by-sector-building-type-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-5-working-hours-by-sector-building-type-and-employee-size-categories.csv)
* [berlin-building-industry-2020-00-6-turnover-in-june-2020-by-sector-building-type-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-6-turnover-in-june-2020-by-sector-building-type-and-employee-size-categories.csv)
* [berlin-building-industry-2020-00-7-turnover-in-2019-by-sector-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-7-turnover-in-2019-by-sector-and-employee-size-categories.csv)
* [berlin-building-industry-2020-00-8-companies-employees-and-turnover.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-8-companies-employees-and-turnover.csv)
* [berlin-building-industry-2020-00-9-key-figures-second-quarter-by-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2020-00/berlin-building-industry-2020-00-9-key-figures-second-quarter-by-employee-size-categories.csv)

### Berlin Building Industry 2021 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/tree/main/data/02-silver/berlin-building-industry-2021-00
* updated: 2025-07-29

**Files**

* [berlin-building-industry-2021-00-1-companies-employees-and-working-hours.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-1-companies-employees-and-working-hours.csv)
* [berlin-building-industry-2021-00-10-key-figures-second-quarter-by-sectors.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-10-key-figures-second-quarter-by-sectors.csv)
* [berlin-building-industry-2021-00-11-working-hours-second-quarter-by-sectors-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-11-working-hours-second-quarter-by-sectors-and-employee-size-categories.csv)
* [berlin-building-industry-2021-00-12-turnover-second-quarter-by-sectors-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-12-turnover-second-quarter-by-sectors-and-employee-size-categories.csv)
* [berlin-building-industry-2021-00-13-turnover-in-2020-by-sector-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-13-turnover-in-2020-by-sector-and-employee-size-categories.csv)
* [berlin-building-industry-2021-00-14-legal-entities-employees-turnover-and-investments-extension-building-industry.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-14-legal-entities-employees-turnover-and-investments-extension-building-industry.csv)
* [berlin-building-industry-2021-00-14-legal-entities-employees-turnover-and-investments-main-building-industry.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-14-legal-entities-employees-turnover-and-investments-main-building-industry.csv)
* [berlin-building-industry-2021-00-2-key-figures-by-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-2-key-figures-by-employee-size-categories.csv)
* [berlin-building-industry-2021-00-3-companies-employees-salaries-by-sectors.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-3-companies-employees-salaries-by-sectors.csv)
* [berlin-building-industry-2021-00-4-employees-by-position.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-4-employees-by-position.csv)
* [berlin-building-industry-2021-00-5-working-hours-by-sector-building-type-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-5-working-hours-by-sector-building-type-and-employee-size-categories.csv)
* [berlin-building-industry-2021-00-6-turnover-in-june-2021-by-sector-building-type-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-6-turnover-in-june-2021-by-sector-building-type-and-employee-size-categories.csv)
* [berlin-building-industry-2021-00-7-turnover-in-2020-by-sector-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-7-turnover-in-2020-by-sector-and-employee-size-categories.csv)
* [berlin-building-industry-2021-00-8-companies-employees-and-turnover.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-8-companies-employees-and-turnover.csv)
* [berlin-building-industry-2021-00-9-key-figures-second-quarter-by-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2021-00/berlin-building-industry-2021-00-9-key-figures-second-quarter-by-employee-size-categories.csv)

### Berlin Building Industry 2022 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/tree/main/data/02-silver/berlin-building-industry-2022-00
* updated: 2025-07-29

**Files**

* [berlin-building-industry-2022-00-1-companies-employees-and-working-hours.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-1-companies-employees-and-working-hours.csv)
* [berlin-building-industry-2022-00-10-key-figures-second-quarter-by-sectors.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-10-key-figures-second-quarter-by-sectors.csv)
* [berlin-building-industry-2022-00-11-working-hours-second-quarter-by-sectors-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-11-working-hours-second-quarter-by-sectors-and-employee-size-categories.csv)
* [berlin-building-industry-2022-00-12-turnover-second-quarter-by-sectors-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-12-turnover-second-quarter-by-sectors-and-employee-size-categories.csv)
* [berlin-building-industry-2022-00-13-turnover-in-2021-by-sector-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-13-turnover-in-2021-by-sector-and-employee-size-categories.csv)
* [berlin-building-industry-2022-00-14-legal-entities-employees-turnover-and-investments-extension-building-industry.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-14-legal-entities-employees-turnover-and-investments-extension-building-industry.csv)
* [berlin-building-industry-2022-00-14-legal-entities-employees-turnover-and-investments-main-building-industry.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-14-legal-entities-employees-turnover-and-investments-main-building-industry.csv)
* [berlin-building-industry-2022-00-2-key-figures-by-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-2-key-figures-by-employee-size-categories.csv)
* [berlin-building-industry-2022-00-3-companies-employees-salaries-by-sectors.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-3-companies-employees-salaries-by-sectors.csv)
* [berlin-building-industry-2022-00-4-employees-by-position.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-4-employees-by-position.csv)
* [berlin-building-industry-2022-00-5-working-hours-by-sector-building-type-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-5-working-hours-by-sector-building-type-and-employee-size-categories.csv)
* [berlin-building-industry-2022-00-6-turnover-in-june-2022-by-sector-building-type-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-6-turnover-in-june-2022-by-sector-building-type-and-employee-size-categories.csv)
* [berlin-building-industry-2022-00-7-turnover-in-2021-by-sector-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-7-turnover-in-2021-by-sector-and-employee-size-categories.csv)
* [berlin-building-industry-2022-00-8-companies-employees-and-turnover.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-8-companies-employees-and-turnover.csv)
* [berlin-building-industry-2022-00-9-key-figures-second-quarter-by-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2022-00/berlin-building-industry-2022-00-9-key-figures-second-quarter-by-employee-size-categories.csv)

### Berlin Building Industry 2023 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/tree/main/data/02-silver/berlin-building-industry-2023-00
* updated: 2025-07-29

**Files**

* [berlin-building-industry-2023-00-1-companies-employees-and-working-hours.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-1-companies-employees-and-working-hours.csv)
* [berlin-building-industry-2023-00-10-key-figures-second-quarter-by-sectors.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-10-key-figures-second-quarter-by-sectors.csv)
* [berlin-building-industry-2023-00-11-working-hours-second-quarter-by-sectors-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-11-working-hours-second-quarter-by-sectors-and-employee-size-categories.csv)
* [berlin-building-industry-2023-00-12-turnover-second-quarter-by-sectors-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-12-turnover-second-quarter-by-sectors-and-employee-size-categories.csv)
* [berlin-building-industry-2023-00-13-turnover-in-2022-by-sector-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-13-turnover-in-2022-by-sector-and-employee-size-categories.csv)
* [berlin-building-industry-2023-00-14-legal-entities-employees-turnover-and-investments-extension-building-industry.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-14-legal-entities-employees-turnover-and-investments-extension-building-industry.csv)
* [berlin-building-industry-2023-00-14-legal-entities-employees-turnover-and-investments-main-building-industry.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-14-legal-entities-employees-turnover-and-investments-main-building-industry.csv)
* [berlin-building-industry-2023-00-2-key-figures-by-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-2-key-figures-by-employee-size-categories.csv)
* [berlin-building-industry-2023-00-3-companies-employees-salaries-by-sectors.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-3-companies-employees-salaries-by-sectors.csv)
* [berlin-building-industry-2023-00-4-employees-by-position.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-4-employees-by-position.csv)
* [berlin-building-industry-2023-00-5-working-hours-by-sector-building-type-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-5-working-hours-by-sector-building-type-and-employee-size-categories.csv)
* [berlin-building-industry-2023-00-6-turnover-in-june-2023-by-sector-building-type-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-6-turnover-in-june-2023-by-sector-building-type-and-employee-size-categories.csv)
* [berlin-building-industry-2023-00-7-turnover-in-2022-by-sector-and-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-7-turnover-in-2022-by-sector-and-employee-size-categories.csv)
* [berlin-building-industry-2023-00-8-companies-employees-and-turnover.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-8-companies-employees-and-turnover.csv)
* [berlin-building-industry-2023-00-9-key-figures-second-quarter-by-employee-size-categories.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-industry-yearly-source-aligned/main/data/02-silver/berlin-building-industry-2023-00/berlin-building-industry-2023-00-9-key-figures-second-quarter-by-employee-size-categories.csv)

## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

source-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).