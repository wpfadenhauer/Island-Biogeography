# Island Biogeography
 
The following files include the raw data and R code used in the "Island Biogeography" manuscript (URL/DOI to be updated once manuscript is published). 
Please reach out if you have any questions about content or organization in this repo. 

<br/><br/>
__Raw Data Files:__
1. Oceanic_Islands_Master_Database.xlsx 
    * This is the main database. This Excel spreadsheet version includes notes attached to individual cells that explain the sources of each datapoint (when those datapoints differ from the sources already listed in the manuscript.
2. Oceanic_Islands_Master_Database.csv
    * This is the exact same file as above, just in CSV form. I recommend you use this version if you're going to run any of the code below. 

<br/><br/>
__R Code Files:__ 
1. SEMs_Native.Rmd
    * Code for the piecewise structural equation model (pSEM) that predicts native plant richness on islands. Results of this code are reported in Figure 3A and Table 2. 

2. SEMs_Established.Rmd
    * Code for the pSEM that predicts established plant richness on islands. Results of this code are reported in Figure 3B and Table 2. 

3. SEMs_Invasive.Rmd
    * Code for the pSEM that predicts invasive plant richness on islands. Results of this code are reported in Figure 3C and Table 2.
  
4. Extra_Native_SEMs.Rmd
    * Our dataset had three pairs of correlated variables (see "Model Building" subsection under "Methods" in manuscript). This file shows the steps we took to decide which variable (from each of the three pairs) to use in the SEMs_Native.Rmd file above.
  
5. Extra_Established_SEMs.Rmd
    * This file shows the steps we took to decide which variable (from each of the three correlated pairs) to use in the SEMs_Established.Rmd file above.
  
6. Extra_Invasive_SEMs.Rmd
    * This file shows the steps we took to decide which variable (from each of the three correlated pairs) to use in the SEMs_Invasive.Rmd file above.
  
7. Simulations.Rmd
    * Some of the generalized linear models (GLMs) within the pSEMs (created in the files above) seemed to slightly violated some of the usual assumptions. In this file, we run some data simulations to make sure that the slighly violated assumptions don't invalidate our results. See "Supplemental Methods" in Appendix 1 for more details. 
  
