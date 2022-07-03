# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:


* The purpose of this analysis is to test credit scores against loans to determine how credit scores can be used to predict loan default so that loan providers may make more informed decsions on loan application 
* This analysis used a historical analysis of credit scores and loan health 
* The original dataset had significant more data on healthy loans than unhealthy, which may explain the weaker precision/recall for unhealthy loans in the first model 
* both models used logistic regression, while only the second model was oversampled to provide more data on unhealthy loans 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * high precision for healthy loans (1.0) and good precision for unhealthy (.87)
  * recall is similar with 1.0 for healthy and .89 for unhealthy ones 
  * overall accuracy scores are high, 1.0 for healthy loans and .88 for unhealthy 



* Machine Learning Model 2:
  * same precision for healthy loans (1.0) and for unhealthy (.87) as original model 
  * recall is improved with 1.0 for healthy and 1.0 for unhealthy ones 
  * overall accuracy scores are better, 1.0 for healthy loans and .93 for unhealthy 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* The oversampled model is more accurate, that being said, given the nature of this analysis it is more important to accurately predict unhealthy loans over healthy. Ideally i would like to see a higher accuracy score for the 1's before i would reccommend using this model 

If you do not recommend any of the models, please justify your reasoning.
