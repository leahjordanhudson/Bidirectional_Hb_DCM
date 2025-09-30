# Bidirectional_Hb_DCM
This repository contains de-identified effective connectivity data and the corresponding code used to support the main findings in the Hudson et al. manuscript (DOI : *To be finalised*).

The present study leverages ultra-high field (UHF) functional magnetic resonance imaging (fMRI) and dynamic causal modelling (DCM) to characterise bidirectional habenula effective connectivity under differing negative reward prediction error (RPE) contexts. 

## Reversal learning model
The [Run_PEB_Reversal.m](analysis/Run_PEB_Reversal.m) script reproduces the DCM results of habenula effective connectivity during the reversal learning task.

## Motion prediction model
The [Run_PEB_Motion.m](analysis/Run_PEB_Motion.m) script reproduces the DCM results of habenula effective connectivity during the motion prediction task.

## Comparison plot
The [Comparison_PEB_plots.m](analysis/Comparison_PEB_plots.m) script reproduces the plot comparing the DCM results of habenula effective connectivity during the reversal learning and motion prediction tasks.

## Note
A custom version of `spm_plot_ci` is used to calculate the 95% confidence interval of the model parameter estimates. This is included [here](custom/spm_plot_ci.m).
