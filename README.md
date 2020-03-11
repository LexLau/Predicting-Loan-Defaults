# Predicting-Loan-Defaults

> Author: Alex Lau

## Table of Contents
- [Problem Statement](#Problem-Statement)
- [Executive Summary](#Executive-Summary)
- [Conclusion](#Conclusion)
- [Data Dictionary](#Data-Dictionary)

## Problem Statement

Many Americans will need to borrow money at some point in their lives, whether to pay for school, a car or a home. If borrowers default on their loans, it is unfortunate for both the borrower as their credit score will be ruined, and for the lender, as their loan may not be recovered. It is important for lenders to decrease this risk as much as possible. Can we predict whether a borrower will default using loan and borrower statistics? We will utilize a series of classification models including logistic regression, decision trees, random forest, extra trees, and adaboost to find out. We will be measuring based on sensitivity, the percentage of correctly predicted defaulted loans out of the loans that defaulted. We believe it is worse to predict false negative, that a person will fully pay back their loans, than a false positive, that a person will default. 

## Executive Summary

We being gathering data by heading over to Lending Club's website and downloading statistics from this URL: https://www.lendingclub.com/info/statistics.action. Lending Club requires members be signed in to access these files, but you can create a free account. In our notebook titled Downloading Data we consolidated each of the downloaded quarterly files for the year 2019 into a single dataframe. During early checks, we found that many rows of the dataframe pertained to current active loans and thus did not have a default or fully paid status. These were removed for modeling purposes since they did not contain our desired target variables of fully paid or default/charged off. We then exported the new dataframe into a csv file in our Data folder titled "FullLoanStats". We loaded this new file into our master notebook for exploratory data analysis. This contained 44171 different loans, of which 38672 were fully paid, and the remaining 5499 either charged off or defaulted. 



## Conclusion

sample text

## Data Dictionary

- Lending Club provides a datadictionary on their website: https://resources.lendingclub.com/LCDataDictionary.xlsx which we have downloaded and saved in Data folder as well, titled "LCDataDictionary".