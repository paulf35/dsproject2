# Predicting the Quality of Spanish Wines
Data Source: https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset 

# Overview:
Using the data source provided by Kaggle.com, we need to build a model that can accurately predict the price of a bottle of wine. 

# Data dictionary
The following list is the data dictionary: 
- winery: Winery name
- wine: Name of the wine
- year: Year in which the grapes were harvested
- rating: Average rating given to the wine by the users [from 1-5]
- num_reviews: Number of users that reviewed the wine
- country: Country of origin [Spain]
- region: Region of the wine
- price: Price in euros [€]
- type: Wine variety
- body: Body score, defined as the richness and weight of the wine in your mouth [from 1-5]
- acidity: Acidity score, defined as wine's “pucker” or tartness; it's what makes a wine refreshing and your tongue salivate and want another sip [from 1-5]

## Removed features:
To build our models, we removed the following features: 
- `winery`, `wine`, `country`, `region`

# Explanatory Data: 
