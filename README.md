# Applicants chance of success.

## Overview

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Deep machine learning and neural network is used in this project to reach the goal of presenting interesting information to Aplhabet Soup.

## Results

DATA PREPROCESSING

* In this model the target variable is "Is Successful" which helps to evaluate the financing.
* Features variables:
  APPLICATION_TYPE
  AFFILIATION
  CLASSIFICATION
  USE_CASE
  ORGANIZATION
  STATUS_1
 
 
 * Removed variables:
  EIN
  NAME
  SPECIAL_CONSIDERATIONS
  

COMPILING, TRAINING, AND EVALUATING THE MODE

The three model attempts were specified with 2 layers. In the third attempt, the layers were:
 
 * First layer has 120 neurons.
 * Second layer has 100 neurons.

<img width="585" alt="image" src="https://github.com/CsarCruz/deep-learning-challenge/assets/120423303/b36dd58c-d877-4857-854a-5db787c59637">

With these specifications, I was not able to achieve the target model performance of 75%.

<img width="636" alt="image" src="https://github.com/CsarCruz/deep-learning-challenge/assets/120423303/d4f49df3-6f8d-4116-b0fb-a531304cbc37">

To achieve better model performance, I followed these steps:
* Increase the cutt of value for CLASSIFICATION.
* Increase the cutt of value for APPLICATION_TYPE.
* Decrease the number of neurons to the model.
* Increase the number of nuerons to the model.
* Decrease the epochs to 50.


## Summary

With the database used for analysis, it is difficult to achieve a model performance of 75%. However, increasing the cutoff values for CLASSIFICATION and APPLICATION_TYPE did not help. Working with different parameters will be helpful in achieving the desired performance. Therefore, in addition to knowing the procedure, managing the data is also an important part of achieving satisfactory results.

