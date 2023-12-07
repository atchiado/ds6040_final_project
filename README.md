# ds6040_final_project

## Description
This repository contains two separate Jupyter Notebooks that perform a Bayesian Analysis on goalkeeper salaries in the big five European soccer leagues. 

## Data 
The data used comes from www.fbref.com. The analysis uses data from the 2022-2023 season, including player salaries, basic goalkeeping statistics, and advanced goalkeeping statistics. This data contains 197 observations and can be found in the goalies.csv file in this repository.

## Required Packages
- pymc
- matplotlib.pyplot
- numpy
- pandas
- arviz
- requests
- bs4
- sys

## How to Use
The XXX notebook contains the Python script used to scrape tables from Fbref, combine them into one Pandas DataFrame, and export as a .csv file to be used in analysis. This produces the goalies.csv data found in the repository. To collect different statistics/years, this is the notebook that would be edited.

The XXX notebook contains the Python script used to conduct the analysis of goalkeeper salaries. To run the code, simply run all code blocks and evaluated the output via the produced graphs.

These notebooks can be run entirely on your local machine as is.
