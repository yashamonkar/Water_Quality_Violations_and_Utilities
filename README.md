# Water_Quality_Violations_and_Utilities
Here we analyze trends in drinking water quality violations.
The Exploratory_Analysis_of_the_Data file takes in complete dataset and filters the values and keeps in the ones used in the analysis. The variables inncluded for further analysis include per captia sales of medicines and bottled water, along with the county fips codes and violations in that county. 

The two model variations are total pooling and partial pooling in a state. Further work would inlcude pooling on two level - state and country. Both files are multi-parameters and can accomodate more variables. Note:- The results in these files are for a subset of the data and are not for the whole dataset. 

Transformations - These files do not include transformations and as such depending on the data transformation would need to be used. Note:- Without proper transformations the Stan is likely to face divergent transitions and treedepth exceedences due to the zero inflated violation data.


