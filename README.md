# UK Road Accident Data Analysis

Exploratory data analysis and cleaning of a real-world UK road accident dataset (1.5M+ records, 2005–2014), sourced from Kaggle.

## What this project does

- Cleans and structures a large, messy real-world dataset using Python and Pandas
- Handles missing values with context-aware logic (e.g. distinguishing "not applicable" from "true missing data")
- Visualises accident patterns by severity, time of day, and weather conditions
- Surfaces key findings and flags areas for further investigation

## Tools used

Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

## Key findings

- The majority of accidents are classified as "Slight" severity
- Accident frequency peaks during rush hour (8am and 4–6pm)
- ~80% of accidents occurred in fine weather, likely reflecting how common fine weather days are rather than fine weather being riskier
- Junction control data is missing for ~40% of records, almost entirely because the accident did not occur at a junction

## Dataset

[UK Road Safety Dataset on Kaggle](https://www.kaggle.com/datasets/devansodariya/road-accident-united-kingdom-uk-dataset) (not included in this repo due to file size — see `.gitignore`)

## Notebook

See [`notebooks/analysis.ipynb`](notebooks/analysis.ipynb) for the full cleaning and analysis process.