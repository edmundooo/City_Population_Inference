# Infering City Population from City Data
---

I used beatufiul soup to scrape the Wikipedia page of [each city with a population greater than 100,000](https://en.wikipedia.org/wiki/List_of_towns_and_cities_with_100,000_or_more_inhabitants) to get each city's elevation, area, population, annual precipitation, mean monthly sunshine hours, annual average temperature, latitude and longitude. I then built models to infer city population, using other the other data as features for analysis. Finally, I visualized the data using a world map.

---
### This repository includes the follwing files:



#### Scrape
* __01_Wiki_Scraper.ipynb:__  scrapes and parses Wiki pages, creates Pandas DataFrames of city data and pickles the DataFrames

#### Clean
* __02_EDA_and_Clean.ipynb:__ reads in pickled city data, performs Exploratory Data Analysis, drop unusable data, augments data and pickles the 'cleaned' data

#### Model
* __03_Modeling.ipynb:__ loads data from a pickled file, performs exploratory data analysis, tranforms target (i.e. Population), models the data to make inferences and examines the quality of those models

#### Visualize
* __04_Data_Viz.ipynb:__ loads data from a pickled file, and visualizes features and targets on a map of the world.

#### Presentation
* __Presentation.pdf:__ presentation of process and results
