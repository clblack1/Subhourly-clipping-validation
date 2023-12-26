This code is recreation of the process completed in the paper "Evaluation of irradiance variability adjustments for subhourly clipping correction." In the paper, a mixture of System Advisor Model simulations and post-simulation Excel analysis was used. This is a walkthrough of those steps using the PySAM library to run the simulations from the .json version of the sites exported from SAM. 

This process is shown for only the NIST and NREL sites, as the other locations have information not publically available. The commercial weather data files used to run the simulations are also not provided.

In the folders for each plant, the bias .csv files include the bias comparisons for each weather vendor at each ILR level, including the empirical bias for reference. There is also a corresponding bias .jpg of the data graphed for each site. 
