# Logistic-Regression

Logistic regression is one of the most popular Machine Learning algorithms, which comes under the Supervised Learning technique. It is used for predicting the categorical dependent variable using a given set of independent variables.
Logistic regression predicts the output of a categorical dependent variable. Therefore the outcome must be a categorical or discrete value. It can be either Yes or No, 0 or 1, true or False, etc. but instead of giving the exact value as 0 and 1, it gives the probabilistic values which lie between 0 and 1.

![image](https://user-images.githubusercontent.com/108378037/196953315-4d1a596a-dc7c-4d32-96be-d085add7a953.png)


![image](https://user-images.githubusercontent.com/108378037/196953451-645fb2c9-ac92-45b5-8cc2-e01cecc1827e.png)


SMOTE was used to show how imbalanced dataset can be treated.

Synthetic Minority Oversampling Technique or SMOTE is another technique to oversample the minority class. Simply adding duplicate records of minority class often don’t add any new information to the model. In SMOTE new instances are synthesized from the existing data. If we explain it in simple words, SMOTE looks into minority class instances and use k nearest neighbor to select a random nearest neighbor, and a synthetic instance is created randomly in feature space.

![image](https://user-images.githubusercontent.com/108378037/196954359-66192432-9b32-46cb-ba74-e2813c8916b7.png)

