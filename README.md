
# PLEASE NOTE: The official version of this repository is available at the following DOI: https://doi.org/10.5066/P9XES5OI 


Code for "Human activity drives establishment, but not invasion, of non-native plants on islands"

Corresponding author: William G. Pfadenhauer (wpfadenhauer@umass.edu). Organismic and Evolutionary Biology, University of Massachusetts Amherst. 160 Holdsworth Way, Amherst, Massachusetts 01003, USA

## Information

Repository Type: R markdown scripts

Year of Origin: 2023

Year of Version: 2023

Version: 1.0.0

Digital Object Identifier (DOI): https://doi.org/10.5066/P9XES5OI

USGS Information Product Data System (IPDS) no.: IP-159293

## Suggested Citation for Software

Pfadenhauer, W.G., DiRenzo, G.V., and Bradley, B.A. Code for "Human activity drives establishment, but not invasion, of non-native plants on islands". Version 1.0.0; U.S. Geological Survey software release. Reston, VA. https://doi.org/10.5066/P9XES5OI 




# Abstract
 
The following files include the raw data and R code used in the "Island Biogeography" manuscript (URL/DOI to be updated once manuscript is published). 
Please reach out if you have any questions about content or organization in this repo. 

<br/><br/>
__Raw Data Files:__
1. Oceanic_Islands_Master_Database.xlsx [this file is not anonymous and therefore will be re-added back to the repo following peer review]
    * This is the main database. This Excel spreadsheet version includes notes attached to individual cells that explain the sources of each datapoint (when those datapoints differ from the sources already listed in the manuscript.
2. Oceanic_Islands_Master_Database.csv
    * This is the exact same file as above, just in CSV form. I recommend you use this version if you're going to run any of the code below. 

<br/><br/>
__R Code Files:__ 
1. SEMs_Native.Rmd
    * Code for the piecewise structural equation model (pSEM) that predicts native plant richness on islands. Results of this code are reported in Figure 2A and Table 2. 

2. SEMs_Established.Rmd
    * Code for the pSEM that predicts established plant richness on islands. Results of this code are reported in Figure 2B and Table 2. 

3. SEMs_Invasive.Rmd
    * Code for the pSEM that predicts invasive plant richness on islands. Results of this code are reported in Figure 2C and Table 2.
  
4. Extra_Native_SEMs.Rmd
    * Our dataset had three pairs of correlated variables (see "Model Building" subsection under "Methods" in manuscript). This file shows the steps we took to decide which variable (from each of the three pairs) to use in the SEMs_Native.Rmd file above.
  
5. Extra_Established_SEMs.Rmd
    * This file shows the steps we took to decide which variable (from each of the three correlated pairs) to use in the SEMs_Established.Rmd file above.
  
6. Extra_Invasive_SEMs.Rmd
    * This file shows the steps we took to decide which variable (from each of the three correlated pairs) to use in the SEMs_Invasive.Rmd file above.
  
7. Simulations.Rmd
    * Some of the generalized linear models (GLMs) within the pSEMs (created in the files above) seemed to slightly violate some of the usual assumptions. In this file, we run some data simulations to make sure that the slighly violated assumptions don't invalidate our results. See "Supplemental Methods" in the Supplementary Materials file for more details.
  
8. FigureS2_plots.Rmd
    * The code generates the plots shown in Figure S2 (in the Supplementary Materials). The values plotted here come from the area coefficients generated in the SEMs_Native.Rmd, SEMs_Established.Rmd, and SEMs_Invasive.Rmd files described above. 
  
