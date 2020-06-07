## Language Related


### Skip-Thought Vectors

Submitted on: 22 Jun 2015

Type: Research Paper

Article: https://arxiv.org/pdf/1506.06726.pdf

Reference: https://arxiv.org/abs/1506.06726



## Dealing with Data

### Dealing with Imbalanced Data

Used the Credit Card Fraud Detection Dataset which has only 0.17% of transactions being classified as fraudulent. For imbalanced data, 1. you would have a problem with getting a good accuracy. 2. you would have a performace issue.

To resolve your problems,
1. change the performance metric. 
(Try Using 1. confusion matrix. 2. precision. 3. recall. 4. F1 score. to get better insight.) 
2. change the algorithm. 
(Decision Trees, RF, etc) 
3. Resampling techniques (Oversample minority class. Undersample majority class.)
4. Generate synthetic samples. (SMOTE)

Wrote on: 3 Feb 2019

Type: Medium Article

Data: https://www.kaggle.com/mlg-ulb/creditcardfraud/home
Code: https://www.kaggle.com/tboyle10/methods-for-dealing-with-imbalanced-data

Reference: https://towardsdatascience.com/methods-for-dealing-with-imbalanced-data-5b761be45a18

### Learning from imbalanced data

Majority Class: 


Wrote on: 15 Feb 2018

Type: Blog Article

Reference: https://www.jeremyjordan.me/imbalanced-data/


## Topics that Need to Study in the Future

- Dummy Classifier
- Oversampling.
- Undersampling: It can be good when you have a ton of data. You will remove information that may be valuable.
- Synthetic Samples. (SMOTE, Synthetic Minority Oversampling Technique, etc)
- SMOTE: It "uses a nearest neighbors algorithm to generate new and synthetic data."