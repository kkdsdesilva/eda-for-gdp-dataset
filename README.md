# eda for gdp dataset

## Data Source and Collection:
The GDP by Country dataset is downloaded from [Kaggle](https://www.kaggle.com/datasets/sazidthe1/world-gdp-data). The World Population dataset is downloaded from [Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/world-population-dataset).

## Data Description:
The GDP by Country dataset contains the GDP of 264 countries from 1960 to 2017. The World Population dataset contains the population of 235 countries from 1960 to 2017. Both datasets are in CSV format. 

## Data Cleaning:
There are no missing values in both datasets.

## Data Exploration:
### 1. Identifying countries with fastest growing GDPs

This can be done by looking at the growth rates of each countries. The growth rate of a country is calculated by the following formula: 
$`growth rate = \frac{GDP_{t_2} - GDP_{t_1}}{GDP_{t_1}}`$ .

