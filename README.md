Olympics Data Analysis
This repository contains code and analysis for exploring trends and insights within the Olympics dataset.

Dataset
The dataset includes statistics on athletes, countries, and events from every Olympics from 1896 to 2016. It has details like:

Athlete demographics
Event outcomes
GDP and population data for participating countries
Data sources:

Athlete Events
World GDP
World Population
Notebooks
The analysis is divided into the following notebooks:

Data Cleaning: Handles missing values, fixes incorrect mappings, merges dataset with GDP and population data
EDA: Visualizes medal tally over time, event-wise dominance, home advantage
Modeling: Uses linear regression and KNN models to predict medal counts and athlete sports
Key Insights
USA, Russia, Germany and China are top medal winners, with swimming, diving, wrestling as areas of dominance
There is a positive correlation between GDP and medal tally
Contingent size correlates with medal count
Linear model predicts medal tally with low error
Height, weight data produces accurate predictions for some sports
Usage
To replicate the analysis:

Clone the repository
Download the datasets and save within the data folder
Run the Jupyter notebooks in order
The core libraries used include Pandas, Matplotlib, Seaborn, Statsmodels, Scikit-learn.

Contributors
Vedant Deshpande
