# GEFS (Reforecast) Combiner
## NIU WCS
### Written by: Robert C. Fritzen

## About
This contains a simple python notebook (jupyter) that allows you to obtain data from the GEFS Reforecast v12 set, and merge them into intermediate files necessary to initialize the Weather Research and Forecasting (WRF) model. Additionally, this package allows you to select from GEFS, which time you would like to initialize from (For example, you may choose to initialize a day 4 forecast as your first time step).

Data are obtained from the AWS repository located here: https://noaa-gefs-retrospective.s3.amazonaws.com/index.html

## Requirements
To run the notebook, a simple Anaconda3 installation should suffice, however you will need to download and install a few additional packages:

* xarray
* xesmf
* numpy
* pygrib
* pywinter (pip3 install pywinter -> Needs gfortran)

## Contact
If you have any questions regarding this notebook/repository, you may reach me at rfritzen1@niu.edu