
# Data Product Canvas - Berlin Building Industry yearly (source-aligned)

## Metadata

* owner: Open Data Product
* description: Source-aligned data product providing Berlin building industry data
* updated: 2025-06-16

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

* [Data extractor](../lib/extract/data_extractor.py) extracts data from inout ports
* [Data copier](../lib/transform/data_copier.py) copies and renames extracted data
* [Data CSV converter](../lib/transform/convert_data_to_csv.py) converts Excel files to CSV format
* [Data aggregator](../lib/transform/aggregate_data.py) aggregates data to be used as output ports

## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

source-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).