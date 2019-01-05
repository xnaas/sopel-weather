[![Build Status](https://travis-ci.org/RustyBower/sopel-weather.svg?branch=master)](https://travis-ci.org/RustyBower/sopel-weather)

# sopel-weather
sopel-weather is an weather lookup module for Sopel.

Since Yahoo deprecated their weather API on January 3, 2019, a reimplementation of the weather module was necessary 

## Usage
```
.setlocation london # Sets location by city name
.setlocation w2643743 # Sets location by WOEID (We are prepending w in front of WOEIDs because they collide with zips)
.setlocation 98101 # Sets location by zip code
.weather # Only works if setlocation has been previously run
.weather seattle, us
.weather london
```

## Requirements
```
requests
```