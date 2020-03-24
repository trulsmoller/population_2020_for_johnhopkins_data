### Date created
2020-03-23

### Title
Dataset: population_2020_for_johnhopkins_data.csv

### Description

Dataset with **population numbers for each country in the world** as per early 2020 and a few other metrics.

The data is customized so that it should be easy to join/merge with the popular John Hopkins data found here:

https://github.com/CSSEGISandData/COVID-19

Variables included in 'population_2020_for_johnhopkins_data.csv':

- 'Country'
- 'Continent'
- 'Population'
- 'Density (P/Km²)'
- 'Med. Age'
- 'Urban Pop %

I used a dataset shared on kaggle by Tanu Prabhu and built on it a bit. See Credits.

My modifications included:
- Adding the 'Continent' column manually.
- Changed some of the Country names so that all match the spelling in the John Hopkins data.
- Removed quite a few columns (only kept the ones listed above)

### Files
population_2020_for_johnhopkins_data.csv

### Load
pd.read_csv('population_2020_for_johnhopkins_data.csv', delimiter=";")

### Credits
Thanks to Tanu Prabhu for creating the dataset which I used as a baseline
for my customized dataset.
https://www.kaggle.com/tanuprabhu/population-by-country-2020
 
