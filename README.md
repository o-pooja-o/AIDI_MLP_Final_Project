# AIDI Machine Learning Programming Final Project
## The Severity Prediction Of The Binary And Multi-Class Cardiovascular Disease - A Machine Learning-Based Fusion Approach
#### arXiv link : https://arxiv.org/abs/2203.04921
#### Article link: https://www.sciencedirect.com/science/article/abs/pii/S1476927122000524#
#### Original Git Repo link: https://github.com/hafsa-kibria/Weighted_score_fusion_model_heart_disease_prediction/blob/main/README.md

### Accuracy Mentioned in a research paper by the machine learning models
The highest accuracy for multiclass classification was found as 75%, and it was 95% for binary.
The highest sensitivity for multiclass classification was 0.78, and it was 0.96 for binary.
The highest specificity for multiclass classification was 0.88, and it was 0.94 for binary.
The highest F1-score for multiclass classification was 0.76, and it was 0.95 for binary.
The highest AUC for multiclass classification was 0.83, and it was 0.98 for binary.

## Introduction
In today's data-rich world, healthcare is a treasure trove of patient and disease data. Machine learning is unlocking hidden patterns within this vast information, particularly in predicting diseases like cardiovascular disease (CVD). This research explores fusion models leveraging ML algorithms—neural networks, SVM, logistic regression, decision trees, random forest, and AdaBoost—to diagnose and assess CVD severity. To tackle class imbalance, the RandomOverSampler was used, enhancing classification performance via a weighted score fusion approach. The resulting three fusion models showed promising performance, reaching 75% accuracy for multiclass and 95% for binary classifications. Find the code at: github/hafsakibria/Weightedscorefusion

### Brief introduction about the project or notebook.
This repository tries to replicate the results given below from the research found by Hafsa Binte Kibria and Abdul Matin. We have also contributed to the existing results obtained by the models used in this research paper

## Installation

This notebook requires specific libraries to be installed. Run the following commands in your Google Colab cell:

```python
!pip install tensorflow
```
Also, there are 2 datasets used in this repo, which are multiclassification.csv and binary classification.csv which can be found in content folder of our repository.
In Google Colab add these files in content/sample_data and run cells from the top. 


