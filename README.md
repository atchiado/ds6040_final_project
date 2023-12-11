# ds6040_final_project

## Description
This repository contains two separate Jupyter Notebooks that perform a Bayesian Analysis on goalkeeper salaries in the big five European soccer leagues. 

## Data 
The data used comes from www.fbref.com. The analysis uses data from the 2022-2023 season, including player salaries, basic goalkeeping statistics, and advanced goalkeeping statistics. This data contains 197 observations and can be found in the goalies.csv file in this repository.
- Player: player name
- GA: goals against
- PKA: penalty kick goals against
- FK: free kick goals against
- CK: corner kick goals against
- OG: own goals scored against goalkeeper
- PSxG+/-: post-shot expected goals minus goals allowed
- /90: post-shot expected goals minus goals allowed per 90 minutes
- Cmp%: completion percentage on passes > 40 yards
- Thr: throws attempted
- Launch%_Passes: percentage of passes that travel > 40 yards
- AvgLen_GK: avg length (yds) of goal kicks
- Opp: crosses faced
- Stp%: percentage of crosses into penalty area stopped
- #OPA/90: defensive actions outside penalty area per 90 minutes
- AvgDist: average dist (yds) from goal of defensive actions
- Min: minutes played
- GA90: goals allowed per 90 minutes
- SoTA: shots on target faced
- Saves: number of saves
- Save%: save percentage
- Squad: what squad the player plays for
- Weekly Wages (USD): weekly earnings
- Annual Wages (USD): yearly earnings
- League: what league the player competes in
- Age: player age at the end of the season

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
The Final_Project_Data_Collection.ipynb notebook contains the Python script used to scrape tables from Fbref, combine them into one Pandas DataFrame, and export as a .csv file to be used in analysis. This produces the goalies.csv data found in the repository. To collect different statistics/years, this is the notebook that would be edited.

The Final_Model_Build.ipynb notebook contains the Python script used to conduct the analysis of goalkeeper salaries. To run the code, simply run all code blocks and evaluated the output via the produced graphs.

These notebooks can be run entirely on your local machine as is, provided you edit the file location to save and load the .csv file containing the data.
