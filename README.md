LPP Averaged fMRI English Data
==============================


This repository contains fMRI time-series **averaged accross participants** from [Le Petit Prince fMRI dataset](https://doi.org/10.1038/s41597-022-01625-7.). This allows one to quickly test models on an "average participant" data. 

The individual preprocessed bold files from the 49 English speaking participants available on the [openneuro repository](https://openneuro.org/datasets/ds003643/versions/2.0.7) were averaged. 


## Content:

    bold/    the nine `.nii.gz` files (one file per run) obtained after averaging the bold file from the American participants
    annotation/   copy of the `annotation/EN` folder from the openneuro repository, containing, among others, the timing of words presentation
    code/         copy of the code folder from the openneuro repository.  
    mask_lpp_en.nii.gz     mask computed by 



Christophe Pallier  <christophe@pallier.org>

Refs:

Li, Jixing, Shohini Bhattasali, Shulin Zhang, et al. 2022. “Le Petit Prince Multilingual Naturalistic fMRI Corpus.” Scientific Data 9 (1): 1. <https://doi.org/10.1038/s41597-022-01625-7.>

Bonnasse-Gahot, Laurent, and Christophe Pallier. 2024. “fMRI Predictors Based on Language Models of Increasing Complexity Recover Brain Left Lateralization.” In Advances in Neural Information Processing Systems, edited by A. Globerson, L. Mackey, D. Belgrave, et al., vol. 37.  <http://arxiv.org/abs/2405.17992>

 
