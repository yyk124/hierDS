# hierDS
This repository contains the R implementation of the Hierarchical Data-splitting (HierDS) method presented in the paper titled "HierDS: Hierarchical Feature Selection for High-Dimensional Survival Analysis with Interactions via Data Splitting" by Yinke Yang and Zhouping Li.

Requirement: 
Experiments were performed on a Windows 11 system. And the R statistical computing environment (version 4.4.2) was employed for all analyses, with parallel computing implemented across 8 logical cores using the parallel package to optimize computational efficiency for large-scale simulations.

Contents: 
HierDS.R contains the main R functions for implementing the HierDS method. Users can use these functions to perform high-dimensional survival analysis with interaction terms and control the FDR.

lasso_inference.R included to implement the "debiased lasso" method, sourced from https://web.stanford.edu/~montanar/sslasso/code.html. 

Notes: 
For the comparison method BH_Hierarchy and Knockoff, we use the p.adjust function and knockoff package, respectively.

Knockoff package sourced from https://cran.r-project.org/web/packages/knockoff/index.html.
