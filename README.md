# census_income_prediction


## Contributor :  
Ashutosh Kumar   
[GitHub Profile](https://github.com/Ashutosh27ind)    
#### Email Contact : ashutoshind2017@outlook.com  

#### Environment:   
Python 3.6.8, PLatform : JupyterLab

# Objective of Case Study:  
The objective is to **predict whether income of an individual exceeds 50K USD per year** based on the census data. This is essentially a binary classification problem with two class values as '>50K' and '<=50K' incomes.  

In this project, we will analyse adult US census data from the year 1994 which has been collected and analysed during a research collaboration of US census bureau and the Silicon Graphics, Inc(SGI).   


# Dataset Information:  
Extraction was done by Barry Becker from the 1994 Census database. A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1)&& (HRSWK>0)).
The dataset is taken from the UCI Machine Learning Repository (http://archive.ics.uci.edu/ml/datasets/Adult). It has a total of 48,842 instances and 3,620 with missing values, leaving 45,222 complete data records. Since the dataset nature is imbalanced, so it might be needed to be handled before model building.

# Data Dictionary:  
Listing of attributes:

>50K, <=50K.
  
*age*: continuous.  
*workclass*: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.  
*fnlwgt*: continuous.  
*education*: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.  
*education-num*: continuous.  
*marital-status*: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.  
*occupation*: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.  
*relationship*: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.  
*race*: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.  
*sex*: Female, Male.  
*capital-gain*: continuous.  
*capital-loss*: continuous.  
*hours-per-week*: continuous.  
*native-country*: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.  
  
# Project Pipeline:  

The project pipeline can be briefly summarized in the following steps which is based on popular CRISP DM framework:    
**•	Step1: Data Exploration:** Here, we need to load the data and understand the features present in it. This would help in getting better understanding of the nature of dataset.  
Exploratory data analytics (EDA)- Normally, in this step, we need to perform univariate and bivariate analyses of the data alongwith the extensive visualisations. followed by feature transformations, if necessary. However, you can check if there is any skewness in the data and try to mitigate it, as it might cause problems during the model-building phase.  
**•	Step2: Data Preparation:** We will perform a wide variety of operations to make data clean for our modelling phase here. It may or might not include missing value analysis & treatment, outliers handling, investigate and mitigate for any skewness, data imbalance, perform any transformations, scaling etc.   
**•	Step3.1: Modelling:** We will perform train-test split of dataset for modelling first. This will be followed by selecting the modeling techniques with its assumptions if any. We will here then perform parameters settings of model or hyper tuning of model parameters until we get the desired level of performance on the given dataset.  
**•	Step3.2: Model Evaluation:** We will assess the models using appropriate evaluation metrics. We will chhose an appropriate evaluation metric which reflects our business goal. We will rank the model performance as well before arriving at final model selection with best performance on unseen data. Bias and Variance report will be also generated and statistical test will be performed to validate our model performance. 
