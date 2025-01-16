# Data Mining Assignment - Bankruptcy Prediction

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Tasks Overview](#tasks-overview)
- [Requirements](#requirements)
- [Useful Links](#useful-links)

## Introduction
This project is part of the Data Mining course, focusing on predicting company bankruptcy using financial data. The dataset contains financial indicators from various companies monitored between 2000-2007. The objective is to develop machine learning models to classify companies as bankrupt or not bankrupt.

## Dataset
The paper will make use of processed data collected by
EMIS, a company that provides information on companies in emerging markets.
The data relates to over 10000 firms which have been monitored
since 2000.
The training file provided will contain financial data on the
performance of about 7000 firms for the period 2000-2007. In total the file
consists of 64 features and a class feature on whether these firms
went bankrupt in the next 5 years after the monitoring period, which
is captured by a value of 1 in the last column of each row.



## Project Structure
- **data_mining_assignment.ipynb** – contains the python code 
- **it2021091_predictions.csv** –  predictions from the `test_unlabeled.csv`
- **it2021091_top50.csv** –   top 50 companies most likely to go bankrupt from `test_unlabeled.csv`
- **test_unlabeled.csv** –  test data
- **training_companydata.csv** –  training data


## Tasks Overview

### A) Data Preparation


### B) Classification
 Models used:
 - LogisticRegression
 - GradientBoostingClassifier
 - RandomForestClassifier
 - DecisionTreeClassifier
 - SVC
 


### Train the chosen model


### C) Evaluation of features



## Requirements
Ensure you have the following installed:
- NumPy
- Matplotlib
- scikit-learn
- pandas
- seaborn
- imblearn





## Useful Links
🔗 **Scikit-Learn Resources**  
- 📌 **GridSearchCV** – scikit-learn 1.5.2 documentation  
  [🔗 GridSearchCV](https://scikit-learn.org/1.5.2/modules/generated/sklearn.model_selection.GridSearchCV.html)  
- 📌 **StratifiedKFold** – scikit-learn 1.6.0 documentation  
  [🔗 StratifiedKFold](https://scikit-learn.org/1.6.0/modules/generated/sklearn.model_selection.StratifiedKFold.html)  
- 📌 **LogisticRegression** – scikit-learn 1.5.2 documentation  
  [🔗 LogisticRegression](https://scikit-learn.org/1.5.2/modules/generated/sklearn.linear_model.LogisticRegression.html)  
- 📌 **GradientBoostingClassifier** – scikit-learn 1.5.2 documentation  
  [🔗 GradientBoostingClassifier](https://scikit-learn.org/1.5.2/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)  
- 📌 **RandomForestClassifier** – scikit-learn 1.5.2 documentation  
  [🔗 RandomForestClassifier](https://scikit-learn.org/1.5.2/modules/generated/sklearn.ensemble.RandomForestClassifier.html)  
- 📌 **DecisionTreeClassifier** – scikit-learn 1.7.dev0 documentation  
  [🔗 DecisionTreeClassifier](https://scikit-learn.org/1.7.dev0/modules/generated/sklearn.tree.DecisionTreeClassifier.html)  
- 📌 **Permutation Importance** – scikit-learn 1.5.2 documentation  
  [🔗 Permutation Importance](https://scikit-learn.org/1.5.2/modules/permutation_importance.html)  

🔗 **Other Useful Links**  
- 📌 **Random Forest: A Complete Guide for Machine Learning | Built In**  
  [🔗 Built In Guide](https://builtin.com/machine-learning/random-forest)  
- 📌 **Do I need to normalize (or scale) data for randomForest (R package)? - Stack Overflow**  
  [🔗 Stack Overflow Discussion](https://stackoverflow.com/questions/34072133/do-i-need-to-normalize-or-scale-data-for-randomforest-r-package)
