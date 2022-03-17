# Quantification of Microbial Robusntess
##### R Toolbox for the quantification of the robusntess of cellular functions starting from a high-throughput setup. 

**NOTE**: The purpose of this study is summarized here: https://pubs.acs.org/doi/full/10.1021/acssynbio.1c00615

&nbsp;  
&nbsp;  
Getting started with robustness quantification:
 1. Download the performance script. 
 2. Standardize the growth of the microorganism to the format visible in "CENPK7D.1.xlsx"
 3. Write a legend for the 96-well plate in the same format as "plate_legend_ACS.xlsx" 
 4. Run the first part of the script. 
 5. The second part of the script is needed for yields calculation in case of enzymatic assays. In that case check the format of "CENPK7D_summary.xlsx", "summary_dilutions.xlsx" and "sugar_initial_concentrations.xlsx"
 6. Once the cellular functions are evaluated, they can be saved in a .csv file like here "CENPK7D_phenotype.csv" 
*NOTE* Cellular functions can be growth variables and yields but can also be fluorescence, gene expressions values etc.
 7. Calculate the functions for all the strains and upload the .csv files in the robustness_quantification script. 
 8. Three main ways to calculate robustness of the functions are reported. We generally advise to use the 1st method (Fano factor) but other methods might be more suitable for other datasets. 

&nbsp;  

Cecilia Trivellin, *cectri@chalmers.se*, Industrial Biotechnology Division, Chalmers University of technology

Created: 21-12-8

The scripts were tested with R Version: 1.4.1717© 2009-2021 RStudio, PBC
Mac OS X 11.6.1 
&nbsp;  

--------

Acknowledgment of support: This material is based upon work supported by the Novo Nordisk Foundation grant DISTINGUISHED INVESTIGATOR 2019 - Research within biotechnology-based synthesis & production (#0055044).
Société Industrielle Lesaffre, Division Leaf, is kindly acknowledged for providing the Ethanol Red strain.

&nbsp;  
