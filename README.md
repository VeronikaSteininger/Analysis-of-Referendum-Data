# Analysis-of-Referendum-Data
This project is about to perform and test different methods (spacial visualization, statistic analysis, time series analysis) at two different datasets: mainly the official results of the 2021 Referendum "Deutsche Wohnen und Co enteignen" in Berlin and, for timeseries analysis, the NY houseowner rate from 1984 to 2018.
There are similarities concerning the context: Both datasets deal with the housing issue in capital cities and could be an important basis for further analysis and political decisions.
In this context however, the datasets are treated as testsets to learn different methods and to understand their potentials and limits. 

# Context: 
The referendum „Deutsche Wohnen und Co enteignen“ which took place in 2021 was a radical demand to expropriate large real estate companies and transfer them to public ownership in order to prevent the fundamental right to housing from being undermined by private economic interests.
The referendum was approved by a clear majority. 
Nevertheless, the current Berlin government has not yet formulated a valid law based on it. 

# Key Questions: 

Are there certain patterns for the individual districts?

- Do the peripheric districts vote differently than the center city districts? 
- Are there voting patterns in the eastern and western parts of the city?
- which districts have the highest/lowest approval rating
- which districts have the highes/lowest voter turnout?

# Data

Main Datasets:
„Endgültiges Ergebnis des Volksentscheides über den Beschlussentwurf „DeutscheWohnen & Co enteignen“ am 26. September 2021“
(Final result of the referendum on the draft resolution “Expropriate Deutsche Wohnen & Co” on September 26, 2021)
Election data provided and owned by the „Amt für Statistik Berlin Brandenburg“ which provides Information on all political elections (European, Federal, State, City level and Referendums) governmental data with high level of trustworthyness.
Open access.
https://www.statistik-berlin-brandenburg.de/opendata/Berlin_VE21_W.csv
Meta: 
https://download.statistik-berlin-brandenburg.de/c7d075c58e0cbcd2/b9bb77cf1a37/Berlin_VE21_Meta.pdf
The dataset contains information on Polling stations, Districts, different categories of electoral districts, wether the district belongs to West- or East Berlin, eligible voters, valid votes, unvalid votes and results: yes/no
For geospacial information the dataset is merged on Open Data Regionales Bezugssystem (RBS) 
Wahlbezirke der Wahlen zur Bundestagswahl in Berlin, zum Abgeordnetenhaus von Berlin und zu den Bezirksverordnetenversammlungen am 26. September 2021 
https://daten.berlin.de/datensaetze/geometrien-wahlbezirke-bundestagswahl-abgeordnetenhaus-berlin-2021

Second Dataset:
Homeownership Rate Time Series Collection
Dataset from the U.S. Census Bureau hosted by the Federal Reserve Economic Database (FRED)
Access via kaggle
https://www.kaggle.com/datasets/census/homeownership-rate-time-series-collection/data


# Folder

01 Project Management – Project brief, meta-information on datasets, project description qnd questions

02 Data – (not uploaded due to size issues)

    Original Data: CSV and Shape Files
    Prepared Data: cleaned and merged datafiles

03 Scripts – Jupyter Notebooks 
    6.1 Sourcing Open Data - Referendum Data and Basic checks
    6.2 Exploring Relationships - Visualizations
    6.3 Geographical Visualization with Python - Choroplethmaps
    6.4 Machine Learning Regression Analysis 
    6.5 Machine Learning Clustering
    6.6. Sourcing and analysing time series data - NY homeowner dataset

04 Analysis – Plots and Visualizations

# Libraries
  pandas – Data cleaning, merging, and transformation.
  numpy – Numerical computations and handling arrays.
  matplotlib – Visualization of temporal and state-level patterns.
  seaborn – Statistical visualizations and advanced aesthetics.
  scikit-learn – Regression and clustering (k-means).
  json / geopandas – Integration of spatial data for mapping.
  statsmodels.api.
  
# the visual storyboard was created with tableau public and can be visited here:

https://public.tableau.com/app/profile/vera.stein/viz/AnalysisofRenferendumData/Story1?publish=yes







