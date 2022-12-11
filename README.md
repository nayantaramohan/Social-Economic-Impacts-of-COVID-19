[![GitHub license](https://img.shields.io/github/license/nayantaramohan/data512-project-repo)](https://github.com/nayantaramohan/data512-project-repo/blob/main/LICENSE)

# DATA 512: Human Centered Data Science (Au 2022)

## Social and Economic Impacts of COVID-19 on San Mateo County, CA

## Goal

## Motivation

## Repository tree
```
├── input_data
│   ├── RAW_us_confirmed_cases.csv
│   ├── cdc_masking_mandates_county.csv.zip 
│   ├── 
│   ├── 
│   ├── 
│   └── mask-use-by-county.csv 
├── output_viz
│   ├── 
│   ├──
│   ├──
│   ├──
│   └──
├── LICENSE
├── README.md
└── project-analysis-nmohan.ipynb

```
#### Description
- **LICENSE** : a file that contains an MIT LICENSE for nayantaramohan/data512-course-project repo.
- **project-analysis-nmohan.ipynb** : The Jupyter notebook that consists of all the code with documentation of the preprocessing, data cleaning and data visualization done to achieve the stated goal.

## Input Data & Sources
1. **RAW_us_confirmed_cases.csv**: The RAW_us_confirmed_cases.csv file from the Kaggle repository of [John Hopkins University COVID-19 data](https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university). This data is updated daily. You can use any revision of this dataset posted after October 1, 2022.
2. **cdc_masking_mandates_county.csv**: The CDC dataset of [masking mandates by county](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i). Note that the CDC stopped collecting this policy information in September 2021.
3. **mask-use-by-county.csv**: The New York Times [mask compliance survey](https://github.com/nytimes/covid-19-data/tree/master/mask-use) data.
4. **Confirmed deaths** from the Kaggle repository of [John Hopkins University COVID-19 data](https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university). 
5. **San Mateo masking mandate** - This data is collected by reading the announcements posted by the San Mateo officials on [smsgoc.org](https://www.smcgov.org/san-mateo-county-reopening) 
6. **Percentage of single dose vaccines** being administered - This data is also collected by monitoring the state's official dashboard for vaccines being administered at [smchealth.org](https://www.smchealth.org/post/vaccination-totals-locations-data)
7. **Housing Rate** - This dataset contains the median listing price in a given market during the specified month for San Mateo County. Using this dataset we can analyze the economic effect due to the pandemic.
8. **Unemployment Rate** - This dataset can be used to answer the economic effect of the pandemic to see if it was affected and by how much during different stages of the pandemic.

## Special Considerations
- Daily confirmed data has been converted into Weekly data by taking a rolling average over 7 days to smoothen the curve and ensure a more effective data visualization.
- Apart from the CDC masking mandate data, San Mateo's [official website](https://www.smcgov.org/san-mateo-county-reopening) stating the masking policies have also been considered in the output visualization.

## Snapshot of Analysis Output

## Best practices for documentation
- PEP 8 – Style Guide for Python Code ([Reference link](https://peps.python.org/pep-0008/))
- Use of relative path addresses to help in reproducibility
- Use of intuitive variable and function names to ease in understanding
- Appropriate comments and documentation provided for the data aquisition, data processing and data analysis steps
- Description of all data files present in the repository mentioned

## Licenses

## Author
[Nayantara Mohan](https://github.com/nayantaramohan) 
