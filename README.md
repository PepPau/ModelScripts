# RGM Model Scripts
This repository contains scripts with the R code used to build, check, and apply new data to the RGM model that makes part of my PhD thesis entilted "The RG niche: deciphering key mechanotransduction components". 
We have developed the radial glia mimetic (RGM) model to characterize RG cells based on nuclear parameters and cell density. 
Cell nuclei were obtained from primary enriched astrocyte cultures that were seeded onto ln2PMMA, a biomaterial that mimics the neurogenic niche 
(see Mattotti, M., Alvarez, Z., Ortega, J.A., Planell, J.A., Engel, E., and Alca´ ntara, S. (2012). Inducing functional radial glia-like progenitors from cortical astrocyte cultures using micropatterned PMMA. Biomaterials 33, 1759–1770. https://doi.org/10.1016/j.biomaterials.2011.10.086.)

To further apply this codes to new data the user should take into account of variables name used for each script. 
If required, you can email me and I can provide the data used for fitting and extra scripts to easily adapt your new data to the provided code. 

If you need an example to see how to apply and perform sequentally the code, do not hesitate to email me. 
The numbers at the begining of each script indicate the order to follow. 

# Scripts
## 0. Packages, libraries, read fitting
This sript does provides all packages and libraries used. It also reads the data used for fitting the model and creates the first main variables. 
## 1. RGM Model construction
This script constructs the RGM model based on a binary response determined by neural cell-type molecular markers, nuclear morphology parameters, and cell density.
After this step, here, the user should upload its own data. Note that the procedure it is not automathized, and the following scripts should be applied one by one to each dataframe.
## 2. To explore extrapolated data
This script provides different subsections to explore extrapolated data and to observe compare graphically if the new data is within the data used for fitting the model.
## 3. RGM model function applied to Control and Ln2PMMA data
This script allows to apply the RGM model function to control and ln2PMMA data. It also provides density/probability line plots with percentage over 33% (1/3) and 50% (1/2) of probability to be RG cells.
## 3.bis RGM model function applied to data with a single substrate
Provides the same as 3. but this allows to apply the model to data with only one substrate.
## 4. Function to calculate LogOdds ratio function
This script creates the function to obtain LogOdds ratio function
## 5. LogOdds Ratio function and levels
This script provides of levels F(0), F(-0.1), and F(-0.25) from the logOdds function ratio. 
Also plots the whole associated levels (the total amount of levels can be manually modified).
## 6. Application of LogOdds ratio function
This script serves to apply the logOdds ratio function to different datasets. 
Provide a graphical outcome with individual points associated to different colors depending on their location, above F(0) or above F(-0.1). Also provides the percentage associated to colored points within  the area range established by Pax6 maximum-minimum areas.

# Contact
Jose Pablo Soriano Esqué 
psoriano@ub.edu
Neural Development Lab
Department of Pathology and Experimental Therapeutics, University of Barcelona. 

