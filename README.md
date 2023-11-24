# Mental Health Tracker
This repository contains a Python script (MH_tracker.py) for tracking and analyzing mental health data. 
The script utilizes machine learning techniques, specifically a Gradient Boosting Regressor, to predict Disability-Adjusted Life Years (DALY) based on various mental health prevalence indicators.
## Files
**MH_tracker.py:**
1. This is the main source code file.
2. It loads and merges two datasets, preprocesses the data, trains a Gradient Boosting model, and evaluates its performance on a validation set.
3. Finally, it prints key performance metrics such as Mean Squared Error, Mean Absolute Error, and R-squared.

**mental-and-substance-use-as-share-of-disease.csv:**

This dataset contains information about the share of mental and substance use disorders in total disease burden. 
It includes columns for Country, Code, Year, and DALY (Disability-Adjusted Life Years).

**prevalence-by-mental-and-substance-use-disorder.csv:**

This dataset provides prevalence rates for specific mental health disorders, including Schizophrenia, Bipolar disorder, Eating disorders, Anxiety disorders, Drug use disorders, Depressive disorders, and Alcohol use disorders.
It includes columns for Country, Code, Year, and individual disorder prevalence rates.

**Mentalhealth_project.pdf:** 

This document is the project report, providing additional context, methodology, and findings related to the mental health tracking project.
