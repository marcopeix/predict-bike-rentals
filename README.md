# Predicting Bike Rentals

Bike sharing is now a common mean of transportation. This project investigates which model can predict bike rentals accurately. For that purpose, the dataset used compiles different information about bike rentals in the city of Washington D.C. The dataset can be downloaded from [here](http://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset).

Some of the relevant columns are:
* `instant` - An ID for each row
* `dteday` - The date of the rentals
* `season` - The season. It can be:
    * `1`: spring
    * `2`: summer
    * `3`: fall
    * `4`: winter
* `year` - Year the rental occured. It can be:
    * `1`: 2011
    * `2`: 2012
* `mnth` - Month of the rental
* `hr` - Hour of the rental
* `holiday` - Whether it was a holiday or not
* `weekday` - The day of the week (1 to 7)
* `workingday` - Whether it was a working day or not
* `weathersit` - The weather. It can be:
    * `1`: Clear
    * `2`: Mist
    * `3`: Snow
    * `4`: Rain
* `temp` - Normalized temperature
* `atem` - Adjusted temperature
* `hum` - Normalized humidity
* `windspeed` - Normalized wind speed
* `casual` - Number of people renting a bike without being signed up
* `registered` - Number of people renting a bike and being registered
* `cnt` - Total number of bike rentals (`casual` + `registered`)

**Objective:** The objective is to identify the best machine learning model to predict the total number of bike rentals for a given time of the day.

**Techniques used:**
* Pandas, matplotlib
* Linear regression
* Decision tree regressor
* Random forest regressor
