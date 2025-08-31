# LPP Averaged fMRI English Data


Christophe Pallier  <christophe@pallier.org>  Aug. 2025


This repository contains fMRI time-series **averaged accross participants** from [Le Petit Prince fMRI dataset](https://doi.org/10.1038/s41597-022-01625-7.).

The individual preprocessed bold files from the 49 English speaking participants available on the [openneuro repository](https://openneuro.org/datasets/ds003643/versions/2.0.7) were averaged, allowing one to perform analyses on an "average participant" data. 



## Content:

    bold/    the nine `.nii.gz` files (one file per run) obtained after averaging the bold file from the American participants
    annotation/   copy of the `annotation/EN` folder from the openneuro repository, containing, among others, the timing of words presentation
    mask_lpp_en.nii.gz     global mask of voxels of interest
    rois_maks/    masks of some regions of the language network


## Reference

Li, Jixing, Shohini Bhattasali, Shulin Zhang, et al. 2022. “Le Petit Prince Multilingual Naturalistic fMRI Corpus.” Scientific Data 9 (1): 1. <https://doi.org/10.1038/s41597-022-01625-7.>


## Some papers using this dataset


Bhattasali, Shohini, Murielle Fabre, Wen-Ming Luh, et al. 2019. “Localising Memory Retrieval and Syntactic Composition: An fMRI Study of Naturalistic Language Comprehension.” Language, Cognition and Neuroscience 34 (4): 491–510. <https://doi.org/10.1080/23273798.2018.1518533.>

Pasquiou, Alexandre, Yair Lakretz, John T. Hale, Bertrand Thirion, and Christophe Pallier. 2022. “Neural Language Models Are Not Born Equal to Fit Brain Data, but Training Helps.” Proceedings of the 39th International Conference on Machine Learning, June, 17499–516. <http://www.unicog.org/publications/Pasquiou et al. - Neural Language Models are not Born Equal to Fit B.pdf'.>


Bonnasse-Gahot, Laurent, and Christophe Pallier. 2024. “fMRI Predictors Based on Language Models of Increasing Complexity Recover Brain Left Lateralization.” In Advances in Neural Information Processing Systems, edited by A. Globerson, L. Mackey, D. Belgrave, et al., vol. 37.  <http://arxiv.org/abs/2405.17992>

Pasquiou, Alexandre, Yair Lakretz, Bertrand Thirion, and Christophe Pallier. 2023. “Information-Restricted Neural Language Models Reveal Different Brain Regions’ Sensitivity to Semantics, Syntax, and Context.” Neurobiology of Language 4 (4): 611–36. <https://doi.org/10.1162/nol_a_00125.>


## Codes

### Nilearn examples

* https://nilearn.github.io/stable/auto_examples/00_tutorials/plot_single_subject_single_run.html#sphx-glr-auto-examples-00-tutorials-plot-single-subject-single-run-py

* https://github.com/l-bg/simple_composition_fmri/blob/master/main.ipynb
 
### Specific to Le Petit Prince

* https://github.com/chrplr/lpp-scripts3  (no longer work as is, because nistats was deprecated and is not part of nilearn)

* https://openneuro.org/datasets/ds003643/versions/2.0.7

* https://github.com/l-bg/llms_brain_lateralization

* https://github.com/AlexandrePsq/LePetitPrince

* https://github.com/AlexandrePsq/Information-Restricted-NLMs.git



