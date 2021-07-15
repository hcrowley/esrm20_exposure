# European Exposure Model

This is a public repository that contains the data and resources being used to develop the exposure models for the European Seismic Risk Model 2020 (ESRM20). 

### Explanation of Repository

The following explains in more detail the folders included in this repository. It is strongly recommended to consult first the "European_Exposure_Model_Data_Inputs_Sources.xlsx" file in the sources folder to better understand how the different files in this repository are combined to produce the exposure models.  

_exposure_models: this folder contains exposure model data for residential (Res), commercial (Com) and industrial (Ind) buildings in 44 countries in Europe

com_building_area: this folder has .csv files, for each country, with the assumptions of the area per building for each commercial building class 

com_exposure_source_data: this folder has .csv files, for each country, with the number of offices, trade (retail) and hotel buildings in each administrative unit obtained from the original source data

com_mapping_schemes: this folder has .xlsx files with the modelled distribution of offices, trade (retail) and hotel buildings per building class

ind_exposure_source_data: this folder has .csv files, for each country, with the number of industrial buildings in each administrative unit / 30 arc second grid cell obtained from the original source data

ind_mapping_schemes: this folder has .xlsx files with the modelled distribution of industrial buildings per building class

res_dwelling_area: this folder has .csv files, for each country, with the assumptions of the area per dwelling for each residential building class 

res_dwelling_per_building: this folder has .csv files, for each country, with the assumptions of the number of dwellings per building for each residential building class 

res_exposure_source_data: this folder has .csv, .xlsx and zip files with the source residential dwelling/building and population data per administrative unit for each country

res_mapping_schemes: this folder has .xlsx and.txt files that describe the distribution of residential buildings/dwellings between building classes.

seismic_design_shapefiles: this folder has shapefiles which map, for each country and design code, the distribution of lateral force coefficients assumed in the model. For more information refer to https://t.co/hQ8Q2tfpfx?amp=1

social_indicators: this folder contains the most recent social indicator data for European countries, as well as the model used for the distribution of the total population between residential and non-residential buildings during the day, night and transit times.

sources: this folder contains an .xlsx file with detailed information on the sources and assumptions used to develop the exposure model.


### Versioning

Please consult the 'WhatsNew.txt' file for a summary of the data released with each version of the model. 

Each version of the European Exposure Model that is released can be accessed by changing from the 'Master' branch to the tag of a given version. 
The Master branch contains the work-in-progress of the next version of the model. 

### References and Citation

Please refer to the following references for more details on the development of the exposure models:

SERA Deliverable D26.3 (Methods for developing European commercial and industrial exposure models, and residential model update), 
Available from URL: http://eu-risk.eucentre.it/wp-content/uploads/2019/08/SERA_D26.3_Exposure_Models_Non-res_Res.pdf

Crowley H, Despotaki V, Rodrigues D, Silva V, Toma-Danila D, Riga E, Karatzetsou A, Sousa L, Ozcebe S, Zugic Z, Gamba P (2020) 
“Exposure model for European Seismic Risk Assessment,” Earthquake Spectra, doi: https://doi.org/10.1177/8755293020919429

Please cite the current version of this repository as: H. Crowley, V. Despotaki, D. Rodrigues, V. Silva, C. Costa, D. Toma-Danila, E. Riga, A. Karatzetzou, S. Fotopoulou, L. Sousa, S. Ozcebe, P. Gamba, J. Dabbeek, X. Romão, N. Pereira, J. M. Castro, J. Daniell, E. Veliu, H. Bilgin, C. Adam, M. Deyanova, N. Ademović, J. Atalic, B. Bessason, V. Shendova, A. Tiganescu, D. Toma-Danila, Z. Zugic, S. Akkar, U. Hancilar and Exposure Contributors (2020). European Exposure Model Data Repository (Version 0.9) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.4062044

For the full list of 'Exposure Contributors' see: https://eu-risk.eucentre.it/contributors/. 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4062044.svg)](https://doi.org/10.5281/zenodo.4062044)

### Contact Us

If you have any questions or feedback on the data included in this repository, please send it via email to 'efehr.risk@sed.ethz.ch'.
