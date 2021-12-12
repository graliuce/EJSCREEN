# EJSCREEN

The data used in this project is freely available to download here: https://www.epa.gov/ejscreen/download-ejscreen-data

In order run the notebook, you must have GeoPandas installed in a conda environment

## Instructions for installing GeoPandas
https://geopandas.org/en/stable/getting_started/install.html

## Instructions for Downloading Data
1. Go to https://gaftp.epa.gov/EJSCREEN/
2. Click 2020 to enter the directory
3. Click EJSCREEN_2020_StatePctile.gdb.zip to download the zip file
4. Unzip the downloaded file.
5. Place EJSCREEN_2020_StatePctile.gdb in the same directory as the EJ_classifier.ipynb

The jupyter notebook should be ready to run! 



Abstract:
This project aims to investigate whether machine learning algorithms can classify community blocks as majority low-income or not majority low-income based
on environmental hazard indexes using the ECJSREEN database. The classification methods compared include naive Bayes, logistic regression, decisions trees,
random forest, and XGBoost, and a neural network An emphasize on tree-based
classification and feature ranking was used identify features that are the best indicators of income status. We also compare models trained on the entire EJSCREEN
dataset with EJSCREEN data for only New Jersey to situate the analysis in a more
local setting. From an environmental justice lens, it is expected that higher rates
of environmental pollution would correlate to lower income levels. Thus, it may
be possible to classify the income status of communities based on their environmental hazard indicators.
