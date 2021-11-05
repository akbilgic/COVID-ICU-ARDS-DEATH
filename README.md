# COVID-ICU-ARDS-DEATH
Loyola

This research aimed to develop machine and deep learning models using both structured clinical data and image data from the electronic health record (EHR) to adverse outcomes following ED admission.
Light Gradient Boosting Machines (LightGBM) was used as the main machine learning algorithm usingclinical data.
Transfer learning from the CheXNet (Rajpurkar et al., 2017) model was implemented on the data. The models followed from https://github.com/jrzech/reproduce-chexnet and https://github.com/brucechou1983/CheXNet-Keras.
The CheXnet model was adopted to predict the risk of COVID-19 infection, Acute Respiratory Distress Syndrome (ARDS), need for ICU admission and mortality. 

The results (AUC) of the proposed models were:

COVID-19: 0.712 (0.627-0.797)
ARDS: 0.741 (0.658-0.824)
ICU Admission: 0.665 (0.578-0.752)
Mortality: 0.759 (0.678-0.840)

This repository contains the relevant files, weights, and scripts to use the transfer learning model to predict the COVID-19 infection, ARDS, ICU admission and mortality. 
