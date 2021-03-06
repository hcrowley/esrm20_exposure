# Spatial Disaggregation Data

The 'ghs_global_250m_Europe.rar' file is the 250 x 250 m resolution built-up area density map in WGS84 released by Pesaresi et al. (2015).

Pesaresi M, Ehrilch D, Florczyk AJ, Freire S, Julea A, Kemper T, Soille P, Syrris V (2015) GHS-BUILT R2015B - GHS built-up grid, derived from Landsat, multitemporal (1975, 1990, 2000, 2014) - OBSOLETE RELEASE. European Commission, Joint Research Centre (JRC) [Dataset] PID: http://data.europa.eu/89h/jrc-ghsl-ghs_built_ldsmt_globe_r2015b. Accessed 24 Apr 2019

This dataset can be used to increase the resolution of the exposure models released herein with the open source spatial disaggregation tool that the EFEHR risk team has developed together with the GEM Foundation, available here: https://github.com/GEMScienceTools/spatial-disaggregation. Users of that tool should replace the downloaded WorldPop .tif file for a given country with this file, ensuring the same name of the file is used. Users are also recommended to configure the parameters in the config_.py file carefully when using this density dataset, rather than the WorldPop population count dataset. For example, we recommend starting with a default value of zero for pop_thresh.
