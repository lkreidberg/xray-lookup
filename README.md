# xray-lookup
This repository contains full posteriors for both instantaneous and lifetime integrated X-ray fluxes as a function of stellar mass and age (calculated in McDonald, Kreidberg, & Lopez 2019). The data are stored as 3-dimensional numpy arrays. 

The "inst_" files are instantaneous X-ray flux as a function of age and stellar mass. The "posterior_" files are lifetime-integrated X-ray flux. The number in the filename, e.g. "175" is the metallicity of the specific table (equal to Z = 0.0175). There are 5 different metallicities. 

The age range spans log(age[yr])= 7.3 to 10. Spacing is roughly 0.18 from 7.3 to 9, and then 0.03 from 9 to 10. 

The stellar masses range frmo 0.3 to 1.4 M_sun, spaced at 0.0264.
