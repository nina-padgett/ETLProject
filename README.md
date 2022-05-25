# Project #2: Extract, Transform, and Load
In this project, we are joining two datasets related to COVID-19 to take a closer look at the US states, their populations, and their case/death counts during the pandemic in 2020.

# Methods Used

# Technologies
Pandas, PostgreSQL

# Contributors
Indranil Roy, Jenna Jorstad, Nina Padgett, and Ying Sun

# Data Sources
COVID-19 Dataset of Case Counts and Death Counts imported directly from website: https://query.data.world/s/vk5mf4hyssjgd5iqtolztihap6xjpi

US County Populations Dataset: uscensuspop2020.csv

# Installation
Code was tested using Python 3.8. The environment also needs pandas and sqlalchemy. The environment was setup as follows:

import pandas as pd
from sqlalchemy import create_engine
