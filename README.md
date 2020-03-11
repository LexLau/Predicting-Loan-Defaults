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

We being gathering data by heading over to Lending Club's website and downloading statistics from this URL: https://www.lendingclub.com/info/statistics.action. Lending Club requires members be signed in to access these files, but you can create a free account. In our notebook titled "Downloading Data" we consolidated each of the downloaded quarterly files for the year 2019 into a single dataframe. During early checks, we found that many rows of the dataframe pertained to current active loans and thus did not have a default or fully paid status. These were removed for modeling purposes since they did not contain our desired target variables of fully paid or default/charged off. We then exported the new dataframe into a csv file in our Data folder titled "FullLoanStats". We loaded this new file into our master notebook for exploratory data analysis. This contained 44171 different loans, of which 38672 were fully paid, and the remaining 5499 either charged off or defaulted. Features we decided to remove for modeling included dates, all data supplied post the approval of the loans since we're attempting to predict during the application process, features where all values were the same, Identification numbers, zip codes that were masked. 

In addition to removing features, we also needed to impute for missing values. In many casses values were not populated because they were not applicable. Individual applications, as opposed to joint applications, would not have values populated where features describe the second applicant because they do not exist. This also mean there were features dependent on another feature being populated. Luckily most of these could simply be set to 0 without disrupting the model, but we made sure no duplicate values existed for joint vs individual applications. Interestingly Joint loans tend to have a higher rate of default at 14.33% compared to individual loans at 12.19%. Loans approved for Joint applications are over 19,000 USD, where individuals are 14,000 USD. Joint apps also have a higher joint debt to income ratios at 18.5 vs 17.5 for individuals. 




## Conclusion

It seems after years of analyzing their data, Lending Club has a good handle on predicting the likelihood of default based on the data retreived on borrowers. They have steadily decreased loan default rates based on historical data from roughly 20% in 2016 to 12% in 2019. The modeling techniques we deployed thus far are unable to both correctly predict loans that will default that Lending Club missed, and at the same time outperform the current accuracy rate of 87.55%. Our most accurate model picks up 80 unfavorable applicants at the expense of 101 favorable applicants. Lenders would need to decide if that is tradeoff they are willing to make. Will the interest earned on the 101 loans make up for the losses resulting from those 80 defaulted loans? Some of the issues that we encountered were the time and computation required to run these models. We also tested other classification models that took too long for our machines. There are also outside factors beyond the scope of the data received during a loan application that can explain why certain borrows default on their loans. One feature that we cannot accurately collect data on that would surely assist with model performance would be applicant's assets. Not all borrowers apply for loans because they do not have the money, some simply want to maintain a healthy emergency cash account. Certainly individuals with higher cash balances would have a higher ability to pay off loans compared to those with lower emergency savings. Some people also have sporadic income, which does not exist as an indicator in our model, but may depend on their employment titles, but there were over 30,000 titles in our dataset. With more time, we can certainly clean up this data to consolidate similar titles, or create groups that perhaps may provide additional insight. There are also unpredictable world events that may cause economic crisis, such as the current COVID-19 pandemic that has sent the travel industry plunging.

## Data Dictionary

- Lending Club provides a datadictionary on their website: https://resources.lendingclub.com/LCDataDictionary.xlsx which we have downloaded and saved in Data folder as well, titled "LCDataDictionary".