# Infering City Population from City Data
---

<img width="608" alt="screen shot 2018-10-02 at 2 42 03 pm" src="https://user-images.githubusercontent.com/25728710/46369580-64c3bc00-c651-11e8-9b98-eb636acb98db.png">

---

### Summary:

The first two IPython notebooks utilize Beatufiul Soup to scrape the Wikipedia pages of [each city with a population greater than 100,000](https://en.wikipedia.org/wiki/List_of_towns_and_cities_with_100,000_or_more_inhabitants) to get each city's elevation, area, population, annual precipitation, mean monthly sunshine hours, annual average temperature, latitude and longitude. Notebook three includes regression models to infer the factors which contribute to city population. Notebook four visualizes the data using a world map.

---
### This repository includes:

* __01_Wiki_Scraper.ipynb:__  scrapes and parses Wiki pages, creates pandas DataFrames of city data and pickles the DataFrames

* __02_EDA_and_Clean.ipynb:__ reads in pickled city data, performs EDA, drop unusable data, augments data and pickles the 'clean' data

* __03_Modeling.ipynb:__ loads data from a pickled file, performs EDA, transforms target (i.e. Population), models the data to make inferences and examines the quality of those models

* __04_Data_Viz.ipynb:__ loads data from a pickled file, and visualizes features and targets on a map of the world

* __Presentation.pdf:__ presentation of process and results

---
