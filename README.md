# ACE592-Team3-Final-Project
## Introduction
This project is the joint work of Wilfried Adohinzin, Allen Hardiman, Theodoros Velentzas, and Yang Yue. 

We explore the Chicago crime data and its relationship with community area level housing prices and Covid-19 cases. 

For the first aspect of our research, the goal is to obtain insights on how the housing market in each community area reacts to changes in criminal activities. Our result shows that the correlations between housing prices and crime vary by community area. Moreover, the correlation becomes more negative as the median housing price increases. We hypothesize that local economic conditions such as infrastructures and amenities may play a role in determining the elasticity of the housing price to crime. 

For the second aspect, we investigate whether stay-at-home order affected the number of incidents for different types of crime. We find that Chicago did not experience any significant changes in homicide, domestic crime, and total crime count over the Covid-19 period. When compared to the pre-Covid-19 era, we find a sizeable reduction in total crime count after the stay-at-home order was enacted. 

## Data Source
The Chicago crime data is extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. It is available for public query via Kaggle/Google Cloud.

The community area level housing price data is obtained from [Zillow](https://www.zillow.com/research/data/). The dataset represents a smoothed, seasonally adjusted measure of typical home value across region and housing type. It reflects the typical value for homes in the 35th to 65th percentile range. 

The population data we use to calculate crime rate for each community area is from the U.S. 2010 Census. It can be accessed via [Chicago Metropolitan Agency for Planning](https://datahub.cmap.illinois.gov/dataset/2010-census-data-summarized-to-chicago-community-areas).

The community area geospatial data we use for plotting is from the [Chicago Data Portal](https://www.kaggle.com/threadid/chicago-shape-files).

Lastly, our Covid-19 data is provided by the [City of Chicago](https://data.cityofchicago.org/Health-Human-Services/COVID-19-Cases-Tests-and-Deaths-by-ZIP-Code/yhhz-zm2v).

## Directory Layout
The "Crime and Housing Prices" iPython Notebook file contains all the code we use for the first aspect of our research. 

The code for our crime and Covid-19 analysis can be found in the "Crime and Covid-19" iPython Notebook. 

And the formal summary of our research is documented in the "Team3_WriteUp" PDF file.  



