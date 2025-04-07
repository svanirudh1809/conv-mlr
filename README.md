# Convolutional Multi-Linear Regression (ConvMLR) model
A hybrid machine learning approach to compute a weighted-ensemble of the Indian summer monsoon rainfall forecasts for improved skill in sub-seasonal scales. Leverages the strengths of an ensemble of the physics-based dynamic model forecasts with learning-based data-driven models to improve the forecast reliability in sub-seasonal time scales (10 - 60 days).
# Datasets
The six configurations of the CFSv2 model -- sasfer, saszc, nsasfer, nsaszc, nsasfer_sc and nsaszc_sc provided by the Indian Institute of Tropical Meteorology (IITM, Pune) are used as the ensemble-member dynamic models.  
Each dynamic model is run every 7 days with a forecast length of 36 days. Hence, 5 different week-leads from each run are concatenated with subsequent week-leads of the models to get a continous dataset (refer to paper or code in the repo).  
The IMERGE dataset is used as the observation dataset for May - Oct in the periods from 2003-2018, where the model forecasts are also available.
# How to Use
Describe how to use and what each file meant to do.
