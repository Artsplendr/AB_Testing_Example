# Example of A/B Testing 

## Overview

This repository contains a notebook with a simple A/B Testing example.  The source of the notebook is  "A/B Testing for Data Science using Python – A Must-Read Guide for Data Scientists" by Shipra Saxena, available at the following link <https://www.analyticsvidhya.com/blog/2020/10/ab-testing-data-science/>.

There is an e-commerce company XYZ. The XYZ team wants to make some changes in its newsletter to increase the traffic on its website. Original newsletter is noted as A and the newsletter with some changes in the text is noted as B.
Both newsletters have the same color, headlines, and overall format.

## Objective

The objective here is to evaluate, which newsletter brings higher traffic on the website i.e the conversion rate. We will use A/B testing and collect data to analyze the newsletters' performance.

## Null hypothesis

The null hypothesis states that there is no difference in the conversion rate in customers, receiving newsletter A and B.

## Alternative Hypothesis

The alternative hypothesis states that the conversion rate of newsletter B is higher than for the newsletter A.

## Control and Test Groups

For this test, we randomly select 1000 customers – 500 each in the Control group and in the Test group (based on random sampling).

## Time Interval for the Test

Since the conversion rate in a group on a certain day represents a single data point, the sample size is actually the number of days (1 month in this case).

## Significance Level

Significance level (alpha) is the probability to reject the null hypothesis, when it is true. Commonly used value is 0.05.

## Confidence Interval

Commonly set to 95%.

## P-value

Calculated for this case is 0.00036, which is less than significance level and we can reject the null hypothesis.



