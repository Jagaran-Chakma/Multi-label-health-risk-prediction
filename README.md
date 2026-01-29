# Multi-label-health-risk-prediction
EDA and Machine Learning

# Project Overview
This project leverages R programming (dplyr, mlr, ggplot2) to analyze the health vulnerabilities of indigenous women associated with water scarcity, 
utilizing multi-label classification algorithms (Binary Relevance, Classifier Chains). The data consists of 120 samples, 
including details such as education level, income status, water source, water availability, purification methods, government program, etc.
By cleaning the data and performing exploratory data analysis (EDA), this project aims to answer key questions that can help to optimize policy-making decisions.

# Objectives
1. To explore how income level, education level, water sources, and other factors influence multiple health outcomes
2. To apply multilabel classification techniques for predicting multiple health problems
3. To compare model performance using standard evaluation metrics
More specifically, Most studies look at one disease at a time, but in reality, individuals often suffer from multiple health conditions simultaneously,
like skin disease, diarrhea, malnutrition, etc., which this study explicitly addressed.

# Dataset Description
# Sample size: 120 respondents
# Data collection method: Purposeful sampling from two selected regions

# Independent variables:
 [1] "edu_level"                     "income_status"                
 [3] "marital_status"                "water_source"                 
 [5] "distance_of_source"            "water_availability"           
 [7] "seasonal_water_shortage"       "purification_method"          
 [9] "water_for_handwashing"         "drink_from_unreliable_sources"
 [11] "govt_programs"              

# Dependent variables:
[12] "others"                       
[13] "diarrhea"                      "skin_disease"                 
[15] "malnutrition"                  "dehydration"                  
[17] "uti"                           "rhi" 
Note: uti = urinary tract infections, rhi = reproductive health issues, and "no health issues" included in "others".

# Methodology
Data cleaning and preprocessing
Exploratory data analysis (EDA)
Statistical modeling (Logistic Regression)
Machine learning models for multilabel classification:
Binary Relevance method
Classifier Chains 

# Evaluation Metrics
The models were evaluated using:
Accuracy
Precision
Recall
F1-score
Hamming Loss

# Key Findings
Income level and water source showed significant associations with health problems.
Multilabel classification enabled simultaneous prediction of multiple health outcomes.
Classifier chains performed better than binary relevance as they captured co-occurrences among labels(disease).
