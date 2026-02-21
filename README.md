# Privacy-Preserving Machine Learning Models for Dementia Classification: An Evaluation of Robustness and Privacy Risks

## Introduction

Artificial Intelligence models have shown promise in accurately classifying dementia, but concerns regarding privacy and security risks associated with these models have emerged. This research proposal aims to develop and evaluate three classification models (Random Forest, Support Vector Machine, and Neural Network) for binary classification of dementia using ADNI data, and assess their robustness against privacy attacks.

## Objectives

The main objectives of this research are as follows:

•	Develop three machine learning models (Random Forest, Support Vector Machine, and Neural Network) for binary classification of dementia using ADNI data, incorporating cognitive assessments, sociodemographics, derived genomics, and imaging data.

•	Evaluate the performance of the models using common evaluation metrics (accuracy, precision, recall, F1-score, ROC-AUC).

•	Assess the privacy risks associated with these models by conducting attribute inference and membership attacks using the AI-SDC package.

•	Develop and implement a custom attack model to simulate potential real-world privacy risks by querying the classification models with both known and random permutations of data.

•	Implement 'safe wrapper' versions of the models provided by AI-SDC to evaluate the impact of privacy-preserving techniques on model accuracy and susceptibility to privacy attacks.

## Data Collection and Pre-processing

The research will utilise the Alzheimer's Disease Neuroimaging Initiative (ADNI) 1 dataset, which includes cognitive assessments, sociodemographics, derived genomics, and imaging data from approximately 200 healthy subjects and 200 subjects with Alzheimer's dementia.
Data pre-processing will involve normalisation, missing value imputation, and feature selection techniques to ensure the quality and relevance of input features for model development. 

## Model Development

a. Random Forest Model

b. Support Vector Machine Model

c. Neural Network Model

Each model will be developed on the pre-processed data with the exact same train/test datasets. The performance of models will be assessed using standard evaluation metrics (accuracy, precision, recall, F1-score, ROC-AUC).

## Privacy Attacks

a. Attribute Inference Attack: Utilise the AI-SDC package to conduct attribute inference attacks to assess whether sensitive information about subjects can be inferred from model outputs.

b. Membership Attack: Use the AI-SDC package to perform membership attacks to determine if an attacker can ascertain whether a particular subject was included in the training dataset.

c. Custom Attack Model: Develop and run a custom attack model to simulate potential real-world privacy risks by querying the classification models with known and random permutations of data.
 

## Privacy-Preserving Techniques

Implement 'safe wrapper' versions of the models provided by AI-SDC to assess the impact of privacy-preserving techniques on model accuracy and susceptibility to privacy attacks.
