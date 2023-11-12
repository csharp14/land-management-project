# land-management-project

PROJECT DESCRIPTION

This project investigates carbon sequestration, specifically by predicting net ecosystem exchange (NEE), which quantifies the exchange of carbon dioxide (CO2) between the land and the atmosphere. Using measurements such as soil moisture and temperature, incoming shortwave radiation, and date as features, the Jupyter notebook land-management-analysis.ipynb contains a few regression models to predict the NEE (the label). The data used for this project is from the Integrated Carbon Observation System (ICOS), for agricultural measurements of the features in farming areas in the locations of Lonzee, Selhausen Juelich, and Voulundgaard.

THE MODELS

Two regression models are included in the Jupyter notebook - LinearRegressor() and HistGradientBoostingRegressor(). The latter can handle missing datapoints, of which there were many in the datasets - this challenge was easy to overcome thanks to the gradient boosting regressor. Two HGBR models are saved here: a first model (HGBR_model.sav) and a model with its hyperparameters tuned to increase the R2 value of prediction trendline (tuned_HGBR_model.sav). These models can be loaded in using pickle (see Jupyter notebook for example).

FUTURE IMPROVEMENTS

Future improvements to the project include modelling the interaction of some of the features in detail, and adding land management activities such as fertilization and pesticide usage.

REQUIREMENTS

The package requirements for the Jupyter notebook are included in the requirements.txt file. 

USING THIS PROJECT

Using this project should be as simple as downloading the repository and running the Jupyter notebook land-management-analysis.ipynb. The notebook contains markdowns and comments to help users follow the code. 

CREDITS

This project was completed in collaboration with Elvira Wikke.

ICOS Carbon portal (https://www.icos-cp.eu/)
