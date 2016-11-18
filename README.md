# BayCount
RCode and Data for the paper BayCount: A Bayesian Decomposition Method for Inferring Tumor Heterogeneity using RNA-Seq Counts

Instructions for Use of the Code:

All figures from the manuscript and the Supplementary Materials are to be reproduced. 

The R script simulation_main_K3.R in the folder /BayCount_Simulation_Code/ BayCount_simulation_K3/ reproduces Figure 2, Figure 3 in the manuscript, and Figure S4 in the Supplementary Material;

The R script simulation_main_K5.R in the folder /BayCount_Simulation_Code/BayCount_simulation_K5/ reproduces Figure 4, Figure 5 in the manuscript, and Figure S8, Figure S9 in the Supplementary Material;

The R script simulation_main_true_K3.R in the folder /BayCount_Simulation_Code/BayCount_simulation_true_K3/ reproduces Figure S1, Figure S2, and Figure S3 in the Supplementary Material;

The R script simulation_main_true_K5.R in the folder /BayCount_Simulation_Code/BayCount_simulation_true_K5/ reproduces Figure S5, Figure S6, and Figure S7 in the Supplementary Material;

The R scripts BayCount_LUSC_preprocess.R, BayCount_LUSC_inference.R, BayCount_LUSC_postprocess.R in the folder /BayCount_TCGA_LUSC_KIRC/ are executed according to the order: 1. BayCount_LUSC_preprocess.R; 2. BayCount_LUSC_inference.R; 3. BayCount_LUSC_postprocess.R, and they reproduce Figure 6, Figure 7 in the manuscript, and Figure S10 in the Supplementary Material;

The R scripts BayCount_KIRC_preprocess.R, BayCount_KIRC_inference.R, BayCount_KIRC_postprocess.R in the folder /BayCount_TCGA_LUSC_KIRC/ are executed according to the order: 1. BayCount_KIRC_preprocess.R; 2. BayCount_KIRC_inference.R; 3. BayCount_KIRC_postprocess.R, and they reproduce Figure 8 in the manuscript, and Figure S11, Figure S12 in the Supplementary Material;

The .RData files LUSC_inference.RData and KIRC_inference.RData for two single MCMC runs over the LUSC dataset and KIRC dataset are available, and one can directly run the R scripts BayCount_LUSC_preprocess.R and BayCount_KIRC_preprocess.R to reproduce the correpsonding figures;

The R script Figure_YX.R in the folder /BayCount_TCGA_LUSC_KIRC/ is to be executed after execution of the R scripts BayCount_LUSC_postprocess.R and BayCount_KIRC_postprocess.R in the same folder. It reproduces Figure 9 in the manuscript, and Figure S13 in the Supplementary Material.
