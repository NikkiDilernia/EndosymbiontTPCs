# EndosymbiontTPCs

TPC Application to cultured Endosymbionts.

This GitHub Repository has been created to deposit code and data as used in a recent TPC study contrasting the thermal performance of cultured coral endosymbiont photo-physiology (Dilernia et al. 2023). Including algorithm evaluation and reporting selection criteria for best model choice, in conjunction with depositing data from TPC studies, allowing for reprocessing at any time using different models for comparison to optimise results. 

All statistical analyses for these TPCs were carried out in RStudio Teams version 2022.07.02 (Build 576), with additional modelling packages “nls.multstart” and “rTPC” integrated by Padfield et al. (2021). The code used for best model selection has been deposited as "TPC Model Selection", and the code used to prepare TPC for the Symbiodiniaceae following selection of best model has been deposited as "FittingChosenTPC".

The csv. files used to run the above code, containing data for the maximum PSII Photochemical Efficiency (Fv/Fm) and effective PSII Photochemical Efficiency in the light (Fq'/Fm'), for three replicates of each of the seven Symbiodiniaceae isolates, has also been deposited. Note that these are named in conjunction with the symbionts "isolate ID" name e.g., "RT141FvFm" for isolate RT141 Fv/Fm data, and "RT141FqFm" for isolate RT141 Fq'/Fm' data. 
