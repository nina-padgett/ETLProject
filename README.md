# Project #2: Extract, Transform, and Load 
In order to have a fair comparison between the US States for COVID-19 infections and deaths, we joined two datasets related to COVID-19 and census data to create a relational database. We took a closer look at the US states, their populations, and their case/death counts during the pandemic. The resulting dataset has two new columns about the percentages of cases and deaths for every state to compare death counts and case counts between each state.

Adding in the two columns of Percent Cases and Percent Deaths gave us better insight of how different states were affected during the pandemic. We believe the percentage comparison gives a clearer picture of the number of deaths in comparison to the case counts in more populated /larger states versus less populated states/smaller states.

# Methods Used
Extract: read csv files
Transform: clean datasets, join datasets, add new columns
Load: load dataframe to database

# Technologies Used
Pandas, PostgreSQL, Jupyter Notebook

# Contributors
Indranil Roy, Jenna Jorstad, Nina Padgett, and Ying Sun

# Data Sources
COVID-19 Dataset of Case Counts and Death Counts imported directly from website: https://query.data.world/s/vk5mf4hyssjgd5iqtolztihap6xjpi
Size: 280mb

US County Populations Dataset: NST-EST2021-POP.csv
location: datasets folder
Size: 1kb

# Installation
Code was tested using Python 3.8. The environment also needs pandas and sqlalchemy. The environment was setup as follows:

import pandas as pd

from sqlalchemy import create_engine
