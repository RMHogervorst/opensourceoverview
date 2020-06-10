# Overview of Open Source Work

This is a guide to my github repo. 
I have a lot of projects and it could be difficult to get an overview.

- [Packages](#Packages)
- [Scraping and machine learning](#Scraping and machine learning)
- [Shiny apps](#Shiny apps)

- [outside contributions](#contributions)

# Packages

## PinboardR
![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
https://github.com/RMHogervorst/pinboardr
https://rmhogervorst.nl/pinboardr/
A package to talk to the pinboard API. 
You can use this package to add new bookmarks, delete them, extract all bookmarks, or to add, modify or remove tags. Basically everything you can do through the website, but from an R session. This is a full implementation of all the endpoints in pinboard.in/api.

## Gephi
![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active) 
![](tidyversestatus)
https://github.com/RMHogervorst/gephi https://rmhogervorst.nl/gephi
This is a simple package to export files into a csv format that gephi can understand. This package does not interface with the open source network vizualisation software gephi but it writes and reads in the same csv format as gephi.

I’ve found the need to convert tidygraph/igraph objects into a node and edge csv, to visualize in gephi quite often. This should be trivial, but gephi is a bit particular and wants specific column names.


## Forensicdatatoolkit
![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
https://github.com/RMHogervorst/forensicdatatoolkit 

These tools merely tell you if the underlying data is probable or not. It can never tell us why the statistics are wrong. Someone could lie or someone could mistype a number. Only open data can tell us which it is.


## banana
![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
https://github.com/RMHogervorst/banana
An exploration of what can be done with the {vctrs} package. This is an implementation of an S3 vector which displays sizes in relative sizes (bananas) but keeps the precise value in cm underneath. 
This allows you to calculate with the real values but keep the display in relative values. 


## IMDB
[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
https://github.com/RMHogervorst/imdb
https://rmhogervorst.nl/imdb/articles/walktrough.html
The package imdb helps you in downloading series and movie information from imdb (it uses the omdbi api). It has three functions one for basic information about series and a second one that also downloads synopsis, actors etc. A third function downloads information about movies.

## gpodder
[![Project Status: Abandoned – Initial development has started, but there has not yet been a stable, usable release; the project has been abandoned and the author(s) do not intend on continuing development.](https://www.repostatus.org/badges/latest/abandoned.svg)](https://www.repostatus.org/#abandoned)
https://github.com/RMHogervorst/gpodder

## musicgraph
[![Project Status: Abandoned – Initial development has started, but there has not yet been a stable, usable release; the project has been abandoned and the author(s) do not intend on continuing development.](https://www.repostatus.org/badges/latest/abandoned.svg)](https://www.repostatus.org/#abandoned)
connect to musicgraph api. another api
https://github.com/RMHogervorst/musicgraph

## A package for house style in coffee colors
[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
https://github.com/RMHogervorst/coffeegeeks
This package contains basic needs for every rstatscoffeegeek.

-    an rmarkdowndocument template with coffee colors and image
-    a ggplot2 coffee theme
-    basic help for when your coffee doesn't taste great
-    coffee related emojis
-    coffee names


# Datasets

## Werewolf dataset
[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
fictional data set of three classes
https://github.com/RMHogervorst/werewolf
I needed a dataset with many interesting features, but mostly where I can probabilistically assign people to three categories.

The people in this dataset can be divided into three categories. They are either normal, werewolf, or wererabbit. All 'normal' measures such as haircolor, BMI, eye color, etnicity, BFI values, blood types, favorite food and allergies match the global values of the USA, Age is a random birthday sample. The names come from the babynames package and are selected from the years between 1960 and 1993. So the general values will be equal to the US population. However I only adjusted the hair and eye values for race, other things are not conditional.

## Unicorns on unicycles dataset
[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
A practice dataset for data munging practice.
https://github.com/RMHogervorst/unicorns_on_unicycles


## Coffee drinking moments 
[![Project Status: Abandoned – Initial development has started, but there has not yet been a stable, usable release; the project has been abandoned and the author(s) do not intend on continuing development.](https://www.repostatus.org/badges/latest/abandoned.svg)](https://www.repostatus.org/#abandoned)
one of my first packages. https://github.com/RMHogervorst/coffeedata


## 
I scraped moviescripts from star trek the next generation and turn that into
a dataset. 

### TNG
[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
TNG dataset, contains every line and every description of all the episodes of TNG
https://github.com/RTrek/TNG

### Speak random sentance from character
[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
https://github.com/RTrek/startrekpackage
This package gives you the option to talk like the main characters of star trek The next generation.
Call the 


# Scraping and machine learning

## Code to scrape the gdpr fines website
https://github.com/RMHogervorst/scrape_gdpr_fines

## Code to extract and parse notes from kindle
https://github.com/RMHogervorst/kindle_notes

## Code to download and extract transcripts of a certain podcast.
[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
Security now podcast. 
https://github.com/RMHogervorst/NLP_SN

- downloading the podcast transcripts
- extraction of relevant information from the transcripts

# code examples
## Code to create XKCD like plot of cities
https://github.com/RMHogervorst/xkcd_weather_cities_nl
Inspired by XKCD. We can determine our ideal city by looking at wintertemperature and humidex (combination of humidity and summer heat). This is a very silly thing to do for the Netherlands, because the country is so small and flat that the weather is approximately the same everywhere.

## Code to add dancing bananas to any picture
[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
http://rmhogervorst.nl/cleancode/blog/2017/11/28/content/post/2017-11-28-building-the-oomsifier/
https://github.com/RMHogervorst/bananafy
The code uses the magic package through the magick wrapper in R. It is a simple script
that turns 

## Code to float a small piece of country away
https://github.com/RMHogervorst/floating_friesland

# Shiny apps

## Karaoke song selector

[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)

https://github.com/Raoke/powrballad
https://rmhogervorst.shinyapps.io/powrballad/

# Contributions
I made a small contribution to apache airflow.
https://github.com/apache/airflow/pull/8240