# UncertProjNotebooks

Author: Alex Chansky
Date: 5/14/21
Description: This folder contains the scripts I used in my spring 2021 uncertainty quantification course.

There is one focus from each of the scripts for this project.
1. my_functions2: Contains bulk of codes used to process import loss data, process into new dataframes, calculate statistics, and produce fragility functions.
2. BetaDistribution: Used to simulate draws from a beta distribution for excitation measures (under the header "Htot Beta Distribution draws"). 
    -- A function "part_2(df,iii)" is then called from the first script, my_functions2 to find CDF parameters for each iteration of beta distribution draws
4. UncertQuantFigures: Used to describe data pulled from beta distribution for each event. These correspond
with figures 3 and 4 of my project. Codes for the figures can be found under the headers, "Intermediate Plot 1" and "Intermediate Plot 2".
4. UncertQuant: Used to describe probability distribution data, confidence intervals, and plot figures 5, 6, 7, 8, and 9.
