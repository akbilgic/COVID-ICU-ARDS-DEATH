# COVID-ICU-ARDS-DEATH
Loyola University Chicago

This research aimed to develop machine and deep learning models using both structured clinical data and image data from the electronic health record (EHR) to adverse outcomes following ED admission.
Light Gradient Boosting Machines (LightGBM) was used as the main machine learning algorithm using clinical data.
In addition, transfer learning from the CheXNet (Rajpurkar et al., 2017) model was implemented on the data. The models followed from https://github.com/jrzech/reproduce-chexnet and https://github.com/brucechou1983/CheXNet-Keras.
The CheXnet model was adopted to predict the risk of COVID-19 infection, Acute Respiratory Distress Syndrome (ARDS), need for ICU admission and mortality. Here we present the model used to predict the four outcomes from chest radiographs.

The results (AUC) of the proposed models were:

COVID-19: 0.712 (0.627-0.797)
ARDS: 0.741 (0.658-0.824)
ICU Admission: 0.665 (0.578-0.752)
Mortality: 0.759 (0.678-0.840)

This repository contains the relevant files, weights, and scripts to use the transfer learning model to predict the COVID-19 infection, ARDS, ICU admission and mortality. The LGBM models will be available at a later date.

Citation:
Butler, L., Karabayir, I., Tootooni, M. S., Afshar, M., Goldberg, A., & Akbilgic, O. (2022). Image and structured data analysis for prognostication of health outcomes in patients presenting to the ED during the COVID-19 pandemic. International journal of medical informatics, 158, 104662.
