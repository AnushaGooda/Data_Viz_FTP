# **SMM635 - Data Visualization (Final Project)**

## **Overview**
""TO BE ADDED""

## **Dataset**
- company-level data on UK-based businesses can be retrieved from the archived of [Free Company Data Product](http://download.companieshouse.gov.uk/en_output.html)

## **Directory Structure**

```
        data-viz-ftp
        ├── README.md
        ├── .gitignore
        ├── requirements.txt
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

### datasets
-   `Industry_codes - Finance.csv` -> 
-   `Industry_codes - Info - Communcation Tech.csv` -> 
-   `Industry_codes - Professional, scientific, technical.csv` ->
-   `London_Borough_Excluding_MHW.json` -> .json file contains London map
-   `cleaned_data.tar.gz` -> `.tar.gz` file contains `cleaned_data.csv`
-   `final_cleaned_data.csv` -> 
-   `industry_added_cleaned_data.csv` -> 
-   `pivot_table_year_cumcount.csv` -> 
-   `tech_industry_added_cleaned_data.csv` -> 
-   `tech_roundabout_coordinates.csv` -> coordinates of companies in tech roundabout by postcode
-   `tech_roundabout_merge.csv` -> 
-   `uk_plotting_data.csv` -> 

### scripts
#### data_preprocessing
-   `00_extract_cleaned_data.ipynb` -> extract `cleaned_data.csv` file from gunzip
-   `01_Select Features.ipynb` -> 
-   `02_final_data_cleaning.ipynb` ->  
-   `03_Industry_cleanup.ipynb` ->  
-   `not_run_data_cleaning.ipynb` ->  clean raw data and create `cleaned_data.csv`
-   `not_run_get_coordinate.ipynb` -> request coordinates from a server


#### visualization
-   `00_tech_city_geospatial_by_sector.ipynb` -> 
-   `01_tech_city_growth_over_time.ipynb` -> 
-   `02_impact_events_visulisations.ipynb` -> 

##### output
-   `sector_comparison_frames` -> 
-   `sector_comparison.html` -> 
-   `events_sector_tech_city.png` -> 
-   `geospatial.html` -> 
-   `lollipop_event_chart.html` -> 
-   `pie.html` -> 
-   `timeline_chart.html` -> 

