___
[Kaggle Competetion](https://www.kaggle.com/c/titanic)
___

# Problem Description
_The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships._

_One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class._

## Data Dictionary

**Variable**|**Definition**|**Key**
:-----:|:-----:|:-----:
survival|Survival|0 = No, 1 = Yes
Pclass|Ticket class|1 = 1st, 2 = 2nd, 3 = 3rd
Sex|Sex|male, female 
Age|Age in years| 
Sibsp|# of siblings / spouses aboard the Titanic| 
Parch|# of parents / children aboard the Titanic| 
Ticket|Ticket number| 
Fare|Passenger fare| 
Cabin|Cabin number| 
embarked|Port of Embarkation|C = Cherbourg, Q = Queenstown, S = Southampton

### Overview

_The data has been split into two groups:_
_training set (train.csv)_
_test set (test.csv)_

_The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features._

_The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic._

__Variable Notes__

__pclass__: _A proxy for socio-economic status (SES)_
_1st = Upper_
_2nd = Middle_
_3rd = Lower_

__age__: _Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5_

__sibsp__: _The dataset defines family relations in this way..._
_Sibling = brother, sister, stepbrother, stepsister_
_Spouse = husband, wife (mistresses and fiancés were ignored)_

__parch__: _The dataset defines family relations in this way..._
_Parent = mother, father_
_Child = daughter, son, stepdaughter, stepson_
_Some children travelled only with a nanny, therefore parch=0 for them._

#### Sample Output
_For each PassengerId in the test set, you must predict a 0 or 1 value for the Survived variable._
