# 270440_Titanic_Challenge
Codacy Badge | [![Codacy Badge](https://app.codacy.com/project/badge/Grade/086c096ceb3943d8b6a9ae246578649c)](https://www.codacy.com/gh/super-user-17/270440_Titanic_Challenge/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=super-user-17/270440_Titanic_Challenge&amp;utm_campaign=Badge_Grade)

## Problem Description
The sinking of the Titanic is one of the most infamous shipwrecks in history. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others. In this challenge, the goal is to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

## Model Used
### Random Forest Classifier
A random forest is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. The sub-sample size is controlled with the max_samples parameter if bootstrap=True (default), otherwise the whole dataset is used to build each tree.

## Outcome
For each entry in test set value 1 or 0 is given to predict if a passenger survived the sinking of the Titanic or not.
PassengerId,Survived
892,0
893,1
894,0
Etc.
