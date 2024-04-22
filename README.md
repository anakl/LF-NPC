This folder contains the following files:

1.revision_code_yieldgaps_clean.R: R script estimating the yield gap between organic and conventional farming due to differences in pesticides use. Please be aware that this script requires access to farm-level FADN data for its execution, which under the EU GDPR regulation cannot be shared by any circumstances to third parties. Nevertheless, to maximize transparency we include the R-script used to calculate the yield gaps. The R-script consists of two main functions: One function calculates the coefficients of the covariates influencing yields and a second one converts the coefficient to a yield gap. The script aligns with the methodology described under "Yield gaps between organic and conventional farming" within the method section.

2.mixed_effect_model.R: R script running the mixed effect model capturing the impact of LF-NPC on yield gap. Please ensure you have the necessary data (“input_npc_yield_gap_data.xlsx”) saved in the same directory as this R script. This will allow you to execute the script without any problems and obtain the same results as presented in the results file called “output_mixed_effect.xlsx”.

3.input_npc_yield_gap_data.xlsx: Excel file containing the data on LF-NPC and yield gaps per crop at regional level (NUTS2). This data is inserted into the mixed effect model “mixed_effect_model.R”.

4.output_mixed_effect.xlsx: Excel file containing the output from ”mixed_effect_model.R”.

5.results_NPC_income.xlsx: Excel file containing the data on a region’s LF-NPC scores and income (baseline and future simulation). The income has been estimated by the CAPRI modelling system. The model is open-sourc - see: https://www.capri-model.org/doku.php?id=capri:install.

6.Source File.xlsx: This Excel file contains the data used to produce all figures and tables of the manuscript and the supplementary material.

7.variation_FADN_regions.xlsx: Excel file containing information on LF-NPC and yield gap (per crop) variations within FADN regions. The variation is captured using various metrics: minimum, maximum, 25th and 75th percentiles, mean, median, and standard deviation. Statistics on the LF-NPC scores are obtained taking into account all agricultural pixels within each region. Yield gap data is presented per crop, with dedicated tabs for each individual crop.
