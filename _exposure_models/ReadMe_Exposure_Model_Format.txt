A brief explanation of the column headers used in the exposure model .csv files is given below, where each row refers to a unique 'asset' (i.e. one or more buildings with similar characteristics at a given location):

LONGITUDE, LATITUDE: Geographical co-ordinates assigned to the asset for risk calculations. In most cases these co-ordinates represent the population weighted centroids of the lowest administrative level available.
TAXONOMY: GEM building taxonomy string that describes attributes that are used to map to the vulnerability functions
MACRO_TAXONOMY: A human-readable and simplified description of the taxonomy
BUILDINGS: The total number of buildings comprising the asset
DWELLINGS: The total number of dwellings (in residential exposure models).
OCCUPANCY: The primary occupancy class (RES/COM/IND)
OCCUPANCY_TYPE: The secondary occupancy class (set equal to "All" where there is no further classification)
SETTLEMENT_TYPE: Urban or rural (in residential exposure models.)
AREA_PER_DWELLING_SQM: The average floor area of a house or dwelling in residential exposure models
AREA_PER_BUILDING_SQM: The average floor area of an establishment in commercial and industrial exposure models
MACRO_TAXONOMY: A simplified description of the building class in terms of main construction material
COST_PER_AREA_EUR: The average replacement cost per unit area (in 2020 EUR/sq.m., including the structural, nonstructural components and building contents)
TOTAL_REPL_COST_EUR: The total replacement cost for the asset (in 2020 EUR, including the structural and nonstructural components and building contents)
COST_STRUCTURAL_EUR: The replacement cost for the structural components of the asset (in 2018 EUR)
COST_NONSTRUCTURAL_EUR: The replacement cost for the nonstructural components of the asset (in 2018 EUR)
COST_CONTENTS_EUR: The replacement cost for the building contents of the asset (in 2018 EUR)
OCCUPANTS_PER_ASSET: The total number of occupants associated with the asset (currently taken from residential population data)
OCCUPANTS_PER_ASSET_DAY: The average number of day-time (10 am to 6pm) occupants of all buildings comprising the asset
OCCUPANTS_PER_ASSET_NIGHT: The average number of night-time (10pm to 6 am) occupants of all buildings comprising the asset
OCCUPANTS_PER_ASSET_TRANSIT: The average number of transit-time (6am to 10am and 6pm to 10pm) occupants of all buildings comprising the asset
OCCUPANTS_PER_ASSET_AVERAGE: The average number of occupants over a 24 hour period for all buildings comprising the asset
NAME_X: Name of the X administrative level

