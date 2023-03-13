# Bloc 6 - Direction de projets de gestion de données

This bloc is to submit the final requirements for the data scientist certificate. The project was done in collaboration with four other certification candidates. The goal was to create and deploy and an app capable of predicting day-to-day electricty consumption in France.

For any inquireies please contact : ymilo.certification@protonmail.com

You will find three relevant links:

- The presentation on the final day of the trainning session : https://www.youtube.com/watch?v=cRNy1-rTXYg&t=2917s
- The slides used during the presentation : https://docs.google.com/presentation/d/1V10sNomsMMYLlvwJbftaKjHNslNxmAU7R3Xtqs5fT3c/edit#slide=id.ga5178bf3d4_2_0
- The link to the streamlit dashboard : https://watt-a-job-app.herokuapp.com/

The file is organised into three directories.

## 0_data_collection_et_master_file

This directory details the data collection procedure to create the necessary datasets. It itseld divided into three sub-directories:

- conso_elec : containning data for electrical consumption in france
- prices : contains the relevant prices for gas, oil and electricty
- weather : contains the coordinates and ipynb files used to create the weather.csv file

## 1_ML

This directory contains the scripts used to test different machine learning models. There are two sub-directories :

- times_series : scripts for time series ml model
- supervised_ml : supervised ml models such as random forest regression (RFR) and linear regression

The seclected model for the project was RFR

## 2_deploiment

This directory contains the files and scripts used to deploy the API and streamlit dashboard.

IMPORTANT NOTE: the datsets and models are too large to be uploaded to github (on average for these files are around 150mb). For the code to work, the archves.zip files must be decompressed and the trainfr.py script run to produce the relevant model saved as "elec.joblib".

There are two sub-directories:

- streamlit: to create the streamlit dashboard
- API: to create the pooject API


