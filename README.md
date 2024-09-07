# ISIC-2024---Skin-Cancer-Detection-with-3D-TBP
[Link to the competition ](https://www.kaggle.com/competitions/isic-2024-challenge)

# Overview

In this competition, we were asked to develop image-based algorithms to identify histologically confirmed skin cancer cases with single-lesion crops from 3D total body photos (TBP). The image quality resembles close-up smartphone photos, which are regularly submitted for telehealth purposes. Binary classification algorithm could be used in settings without access to specialized care and improve triage for early skin cancer detection.

# Dataset Description
The dataset consists of diagnostically labelled images with additional metadata. The images are JPEGs. The associated .csv file contains a binary diagnostic label (target), potential input variables (e.g. age_approx, sex, anatom_site_general, etc.), and additional attributes (e.g. image source and precise diagnosis).

# Objective 

Differentiate benign from malignant cases. For each image (isic_id) assign the probability (target) ranging [0, 1] that the case is malignant.

# Evaluation

Submissions are evaluated on partial area under the ROC curve (pAUC) above 80% true positive rate (TPR) for binary classification of malignant examples
