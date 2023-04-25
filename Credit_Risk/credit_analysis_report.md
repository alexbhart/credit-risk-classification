# Module 12 Report Template

## Overview

 * The purpose of the analysis that was done was to see if we could build a predictive model that using certain parameters, such as the total size of the loan, the interest rate of the loan, income, debt to income ratio, number of currently held accounts, negative marks on their credit report, and total debt could be used to accurately predict whether or not any new borrowers would be considered a healthy candidate for a loan or high-risk.

* Used value_counts() to look at the data skew. The dataset had a very low high-risk count, accounting for only 3.22% of the data. This imbalance led to a less accurate model for predicting high-risk loan applicants.

* Because of this data imbalance, we used an oversampling and resampling methodology to bring the datasets into a more equivocal dimensional space and reran the Logistic Regression models after getting initial results that were less than ideal.

## Results

* The first pass without resampling the data, the model very accurately could predict whether an applicant would be a "healthy" applicant, but was less consistent, at 88% accurate,  at identifying high-risk applicants, which is what we would want to look for.

* After applying an oversampling algorithm to the data and getting equal counts on the 1's and 0's, we ran the same Logistic Regression algorithm over the data and the resultant confusion matrix showed slightly better false results as well as increased accuracy at identifying high-risk applicants.




