# Bias corrected timeseries
Scripts to perform bias correction of temperature time series as described in 
Ortega-Cisneros et al. 2024.  
  
The `scripts` folder contains three `Rmarkdown` files describing how to perform
temperature bias correction under different scenarios, and within two FishMIP
regional model boundaries.  

The `pdfs` folder contains `PDF` versions of the `Rmarkdown` files included in the `scripts` folder. This may be useful for anyone not wanting to run the scripts, but is interested in visualising any figures produced in the scripts.  
  
Most of the data used in this repository is available in the `data` folder, with the exception of `zarr` files. These files include monthly gridded data within the boundaries of regional models, and it is too large to be shared in this repository. However, you
can download data from the "GFDL model outputs" tab of the FishMIP regional model using the following link: 
http://rstudio.global-ecosystem-model.cloud.edu.au/shiny/FishMIP_Input_Explorer/. Make sure data is donwloaded and uncompressed inside the `data` folder before you can run any of the scripts.  
  

