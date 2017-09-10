# case_study2_churn_prediction

## Overview
In this case study, we analyzed a ride-sharing company's data to perform churn prediction. The data is not shared on github since it is obtained from a real company

Data were collected from 3 different cities. Data include info on avg distance, ratings by driver and customers, avg surge, city, last trip date, type of phone used, signup date, surge percent, trips in first 30 days, luxury car used, weekday pct.

## EDA ana analysis
Explored data to find under what conditions high churn rates are observed and what factors are the best predictors for retention. "churn" was defined to be users who have not taken a ride for 30 days or more from the day the data was pulled.

Random forest was used to model the churn prediction, and important  features were identified, which include avg distance traveled, % of trips on weekdays, and % of trips where Surge >1. The ROC curve was then plotted and we achieved 85% True positive rate with 50% false positive rate.

Recommended actions for churn reduction include addressing customer satisfactions (training drivers, followup with customers who were upset) and supplying more cars during surge.  

## Our team
This case study was done by our team: Shige Tajima, Kenny Durell, Jake Hawkesworth, Anusha Mohen.
