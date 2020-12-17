# **SMM635 - Data Visualization (Final Project)**

## Introduction

This final course project deals with the genesis and the transformation of Tech City (aka Silicon Roundabout), one of the most prominent technology-based clusters in the world.

## Problem to address

The students are required to jointly use geospatial analysis and dynamic visualization to represent the emergence and transformation of Tech City. The audience is difficult to frame – the visualization should be included in a blog talking about digital technologies and societies.

## Background for the case study

To deliver the project, students may want to:

- conduct a qualitative/historical investigation of the history of Tech city
- appreciate the existence of key events or policy making decisions that could have represented turning points in the lifecycle of Tech City

## **Dataset**
- company-level data on UK-based businesses can be retrieved from the archived of [Free Company Data Product](http://download.companieshouse.gov.uk/en_output.html)

## **Directory Structure**

```
        data-viz-ftp
        ├── README.md
        ├── .gitignore
        ├── requirements.txt
        ├── companion_document.docx
        ├── datasets
        │   ├── Industry_codes - Finance.csv
        │   ├── Industry_codes - Info - Communcation Tech.csv
        │   ├── Industry_codes - Professional, scientific, technical.csv
        │   ├── London_Borough_Excluding_MHW.json
        │   ├── cleaned_data.tar.gz
        │   ├── final_cleaned_data.csv
        │   ├── industry_added_cleaned_data.csv
        │   ├── pivot_table_year_cumcount.csv
        │   ├── tech_industry_added_cleaned_data.csv
        │   ├── tech_roundabout_coordinates.csv
        │   ├── tech_roundabout_merge.csv
        │   └── uk_plotting_data.csv
        └── scripts
            ├── data_preprocessing
            │   ├── 00_extract_cleaned_data.ipynb
            │   ├── 01_Select Features.ipynb
            │   ├── 02_final_data_cleaning.ipynb
            │   ├── 03_Industry_cleanup.ipynb
            │   ├── not_run_data_cleaning.ipynb
            |   └── not_run_get_coordinate.ipynb
            └── visualization
                ├── output
                │   ├── sector_comparison_frames
                │   ├── sector_comparison.html
                │   ├── events_sector_tech_city.png
                │   ├── geospatial.html
                │   ├── lollipop_event_chart.html
                │   ├── pie.html
                │   └── timeline_chart.html
                ├── 00_tech_city_geospatial_by_sector.ipynb
                ├── 01_tech_city_growth_over_time.ipynb
                └── 02_impact_events_visulisations.ipynb

```

## File Description
-   `requirements.txt` -> Python packages requirements
-   `companion_document.docx` -> companion document
### datasets
-   `Industry_codes - Finance.csv` -> industry codes for companies under finance umbrella
-   `Industry_codes - Info - Communcation Tech.csv` -> industry codes for companies under info tech umbrella
-   `Industry_codes - Professional, scientific, technical.csv` -> industry codes for companies under scientific and technical umbrella
-   `London_Borough_Excluding_MHW.json` -> .json file contains London map
-   `cleaned_data.tar.gz` -> `.tar.gz` file contains `cleaned_data.csv`
-   `final_cleaned_data.csv` -> all data with unnecessary companies and columns removed
-   `industry_added_cleaned_data.csv` -> column addition from external data derived from gov.uk
-   `pivot_table_year_cumcount.csv` -> every year with sector as column titles and cummulative count for each year
-   `tech_industry_added_cleaned_data.csv` -> all data considering only the 17 tech sectors we have chosen
-   `tech_roundabout_coordinates.csv` -> coordinates of companies in tech roundabout by postcode
-   `tech_roundabout_merge.csv` -> coordinates of companies merged with sector data
-   `uk_plotting_data.csv` -> company wise data along with latitude, longitude and company name

### scripts
#### data_preprocessing
-   `00_extract_cleaned_data.ipynb` -> extract `cleaned_data.csv` file from gunzip
-   `01_Select Features.ipynb` -> extract `feature_data.csv` file from gunzip
-   `02_final_data_cleaning.ipynb` ->  extract `final_cleaned.csv` file from gunzip
-   `03_Industry_cleanup.ipynb` ->  extract `industry_added_cleaned_data.csv` file from gunzip
-   `not_run_data_cleaning.ipynb` -> clean raw data and create `cleaned_data.csv`
-   `not_run_get_coordinate.ipynb` -> request coordinates from a server


#### visualization
-   `00_tech_city_geospatial_by_sector.ipynb` -> geospatial visualisation of Tech City
-   `01_tech_city_growth_over_time.ipynb` -> growth of industries over time
-   `02_impact_events_visulisations.ipynb` -> impact of global events on the development of Tech City

##### output
-   `sector_comparison_frames` -> folder contains images for `sector_comparison.html`
-   `sector_comparison.html` -> sector development over real time during the development of Tech City
-   `events_sector_tech_city.png` -> heat map of the impact of different key events on each sector
-   `geospatial.html` ->  sector composition of Tech City with geographical location in the Tech City
-   `lollipop_event_chart.html` -> key events breakdown and its effect on Tech City by sector
-   `pie.html` -> district and sector wise breakdown of Tech City
-   `timeline_chart.html` -> overview of tech sector growth of life of Tech City
