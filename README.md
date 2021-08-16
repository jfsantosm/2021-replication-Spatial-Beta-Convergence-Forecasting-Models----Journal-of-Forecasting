RStudio: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jfsantosm/2021-replication-Spatial-Beta-Convergence-Forecasting-Models----Journal-of-Forecasting/HEAD?urlpath=rstudio)
DOI: https://doi.org/10.1002/for.2816
DOI: 10.1002/for.2816

Suggested citation: Felipe Santos-Marquez. (2021). Spatial Beta-Convergence Forecasting Models: Evidence from Municipal Homicide Rates in Colombia.
Journal of Forecasting. https://doi.org/10.1002/for.2816. 

This work is licensed under the Creative Commons Attribution-Share Alike 4.0 International License.

[![Creative Commons Lizenzvertrag](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)


This repository contains a tutorial to replicate the results of the published paper

## Spatial Beta-Convergence Forecasting Models: Evidence from Municipal Homicide Rates in Colombia

The forecasting power of different methods is tested utilising crime data for 1120 inland municipalities in Colombia.
Using data from 2003 to 2018, five different forecasting methods are used: ETS, ARIMA, STAR, a classical beta convergence based model and a spatial beta convergence model.
First, it is shown that overall municipal crime disparities are steadily decreasing over time.
This indicates that convergence and spatial effects are pivotal for the study of the dynamics of crime in Colombian municipalities.
Time series cross validation for 4-year ahead forecasts is implemented to assess the accuracy of all models.
It is found that the STAR and the beta models have the lowest root mean squared errors.
Therefore, as time goes by, space appears to play a more important role in the evolution of homicide rates.
The paper concludes with some policy implications in terms of spatial effects and the mitigation of crime.

## Online Environments

- This notebook can also be executed online at [GESIS Notebooks](https://notebooks.gesis.org). Just copy the URL of this repository and paste it on the [BINDER form](https://notebooks.gesis.org/binder/) To open a virtual R Studio session, make sure you change you click on `File` and change it to `URL`. Then, write `rstudio` in the field `URL to open (optional)`. Finally, click on `launch`. 

## Replication

In order to replicate the main tables of the article tables 1 and 2, run the Rmd files in the order from a to g.


## sessionInfo()

You may opt to run all the code in your PC, here it is the session info of mine

R version 4.0.4 (2021-02-15)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 19043)

Matrix products: default

locale:
[1] LC_COLLATE=English_United States.1252 
[2] LC_CTYPE=English_United States.1252   
[3] LC_MONETARY=English_United States.1252
[4] LC_NUMERIC=C                          
[5] LC_TIME=English_United States.1252    

attached base packages:
[1] stats     graphics  grDevices utils     datasets 
[6] methods   base     

other attached packages:
 [1] forecast_8.12     REAT_2.1.1       
 [3] readxl_1.3.1      data.table_1.12.8
 [5] broom_0.5.6       modelr_0.1.7     
 [7] forcats_0.5.0     stringr_1.4.0    
 [9] dplyr_1.0.2       purrr_0.3.4      
[11] readr_1.3.1       tidyr_1.0.3      
[13] tibble_3.0.1      ggplot2_3.3.0    
[15] tidyverse_1.3.0   knitr_1.28       
[17] ExPanDaR_0.5.3    devtools_2.3.0   
[19] usethis_1.6.1    

loaded via a namespace (and not attached):
 [1] nlme_3.1-152        fs_1.4.1           
 [3] xts_0.12-0          lubridate_1.7.8    
 [5] httr_1.4.1          rprojroot_1.3-2    
 [7] tools_4.0.4         backports_1.1.6    
 [9] R6_2.4.1            DT_0.13            
[11] mgcv_1.8-33         DBI_1.1.0          
[13] colorspace_1.4-1    nnet_7.3-15        
[15] withr_2.2.0         tidyselect_1.1.0   
[17] prettyunits_1.1.1   tictoc_1.0         
[19] processx_3.4.2      curl_4.3           
[21] compiler_4.0.4      cli_2.0.2          
[23] rvest_0.3.5         xml2_1.3.2         
[25] desc_1.2.0          labeling_0.3       
[27] tseries_0.10-47     scales_1.1.1       
[29] lmtest_0.9-37       fracdiff_1.5-1     
[31] quadprog_1.5-8      callr_3.4.3        
[33] askpass_1.1         digest_0.6.25      
[35] foreign_0.8-81      rio_0.5.16         
[37] pkgconfig_2.0.3     htmltools_0.4.0    
[39] sessioninfo_1.1.1   dbplyr_1.4.3       
[41] fastmap_1.0.1       TTR_0.23-6         
[43] htmlwidgets_1.5.1   rlang_0.4.7        
[45] quantmod_0.4.17     rstudioapi_0.11    
[47] shiny_1.4.0.2       farver_2.0.3       
[49] generics_0.0.2      zoo_1.8-8          
[51] jsonlite_1.7.1      zip_2.0.4          
[53] magrittr_1.5        Matrix_1.3-2       
[55] Rcpp_1.0.4.6        munsell_0.5.0      
[57] fansi_0.4.1         shinycssloaders_0.3
[59] lifecycle_0.2.0     stringi_1.4.6      
[61] pkgbuild_1.0.7      grid_4.0.4         
[63] parallel_4.0.4      promises_1.1.0     
[65] crayon_1.3.4        lattice_0.20-41    
[67] splines_4.0.4       haven_2.2.0        
[69] hms_0.5.3           ps_1.3.2           
[71] pillar_1.4.4        pkgload_1.0.2      
[73] urca_1.3-0          reprex_0.3.0       
[75] glue_1.4.0          remotes_2.1.1      
[77] vctrs_0.3.2         httpuv_1.5.2       
[79] testthat_2.3.2      cellranger_1.1.0   
[81] gtable_0.3.0        openssl_1.4.1      
[83] assertthat_0.2.1    xfun_0.22          
[85] openxlsx_4.1.5      mime_0.9           
[87] xtable_1.8-4        later_1.0.0        
[89] timeDate_3043.102   memoise_1.1.0      
[91] ellipsis_0.3.0  
