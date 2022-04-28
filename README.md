# 304-the-final
304 final paper
# A Study of Toronto's Apartment Ratings, 2021

  - Authors: Yichun Zhang
  - Date: April 27, 2022
  - Email: kimberlyzyc.zhang@mail.utoronto.ca

## Overview of the paper

This repository study the potential factors that impact the score of Toronto's Apartments, using the data from "Open Data Toronto", 2021
## Repo structure

- 'scripts' includes a data simulation.
- 'inputs' contains the datasheet pdf which gives some information on how the dataset was created, the rmd file used to produce the pdf.
- 'outputs' contains the rmd and pdf of the paper, as well as the bib file for the references used.

## Obtaining data

The data was retrieved from 'Open Data Toronto' website which is a digital data that is initiative by the City of Toronto government and it is made available with the technical characteristics necessary for it to be freely used.
  
## Preprocessing and Cleaning

After loading the data into R, we mutated a factored called id so that each data is correlated with an unique id. We also stored the key variables we want to use to a data set called clean. We cleaned names of each variables using clean_name function from janitor. 
