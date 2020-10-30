#GLOFsusceptibility

This repository contains the source code, as well as the two needed data sets to run it, to estimate susceptibility of Hindu-Kush Karakoram Himalaya (HKKH) glacier lakes to GLOFs in the past four decades. The code describes four Bayesian multi-level logistic regressions, in which we encoded and test the potential influences of characteristics such as glacier lake area and its dynamics, catchment area, regional glacier-mass balances and monsoonality on a given lake's GLOF history. The script, which is deposited as a commented Rmarkdown-file, has to be run in R (https://www.r-project.org/) and RStudio (https://rstudio.com). Data compiled in the two data sets is freely available from following sources: 

- Shuttle Radar Topography Mission (SRTM) from the US Geological Survey (https://www.earthexplorer.usgs.gov) 
- CHELSA Bioclim data set (https://chelsa-climate.org/bioclim/): Karger, D. N., Conrad, O., Böhner, J., Kawohl, T., Kreft, H., Soria-Auza, R. W., Zimmermann, N. E., Linder, H. P. and Kessler, M.: Climatologies at high resolution for the earth’s land surface areas, Sci. Data, 4, 1–20, doi:10.1038/sdata.2017.122, 2017. 
- regional glacier-mass balances: Brun, F., Berthier, E., Wagnon, P., Kääb, A. and Treichler, D.: A spatially resolved estimate of High Mountain Asia glacier mass balances from 2000 to 2016, Nat. Geosci., 10(9), 668–673, doi:10.1038/ngeo2999, 2017.
- glacier lake inventories: Maharjan, S. B., Mool, P. K., Lizong, W., Xiao, G., Shrestha, F., Shrestha, R. B., Khanal, N. R., Bajracharya, S. R., Joshi, S., Shai, S. and Baral, P.: The Status of Glacial Lakes in the Hindu Kush Himalaya, Kathmandu., 2018.
Wang, X., Guo, X., Yang, C., Liu, Q., Wei, J., Zhang, Y., Liu, S., Zhang, Y., Jiang, Z. and Tang, Z.: Glacial lake inventory of High Mountain Asia (1990–2018) derived from Landsat images, Earth Syst. Sci. Data Discuss., (January), 1–23, doi:10.5194/essd-2019-212, 2020.
- GLOF inventories: Veh, G., Korup, O., Specht, S., Roessner, S. and Walz, A.: Unchanged frequency of moraine-dammed glacial lake outburst floods in the Himalaya, Nat. Clim. Chang., 2000, 1–5, doi:10.1038/s41558-019-0437-5, 2019.


## BMR_GLOFs_HKKH.Rmd

Commented script written in R describing the setup, output, and predictive oerformance of four Bayesian multi-level logistic regression models which encode the potential influence of topographical, glaciological, and monsoonal drivers on GLOF susceptibility of HKKH lakes in the past four decades.

## GLOF_HKH_Sep2020_2.csv

This data set has to be loaded into the script included in BMR_GLOFs_HKKH.Rmd. It contains 25 lake characteristics for an inventory of 3390 glacier lakes in the HKKH. 

## GLOFDataAll_Dates_GLIMS.txt

This data set has to be loaded into the script included in BMR_GLOFs_HKKH.Rmd. This file contains 107 characteristics for an inventory of 3390 glacier lakes in the HKKH

## References

Fischer, M., Korup, O., Veh, G. and Walz, A.: Controls of outburst of Himalayan moraine-dammed lakes. The Cryosphere (submitted).

## Contact

Melanie Fischer
DFG research training group NatRiskChange
University of Potsdam
melaniefischer@uni-potsdam.de
