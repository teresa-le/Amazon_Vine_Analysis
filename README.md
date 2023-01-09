# Amazon Vine Analysis

## Purpose
The purpose of this analysis is to analyze Amazon reviews to determine whether reviewers who are a part of Amazon's Vine program (i.e. being paid) are biased and writing more favourable reviews than unpaid reviewers.

The dataset used in this analysis is Amazon's health personal care products reviews dataset. 

## Results
To avoid division errors and only examine reviews that have been deemed helpful, reviews with less than 20 votes and have a helpfulness percentage score of less than 50% were removed. 

After analyzing a subset of the dataset, I found the following: 
* In total, there were 462 Vine reviews and 107,971 non-Vine reviews. 
* 203 of the Vine reviews were 5 stars, and 66,755 of the non-Vine reviews were 5 stars. 
* 44% of the Vine reviews were 5 stars whereas 62% of non-Vine reviews were 5 stars.

## Summary 
Vine (paid) reviewers weren't biased towards the products that they were reviewing. Non-Vine (unpaid) reviewers gave more favourable reviews than Vine reviewers (62% vs. 44%)

To provide further support for this statement, additional analyses can be conducted to compare the average star review ratings and percentage of 1 star review ratings by type of reviewer. 