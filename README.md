# Credit_Risk_Machine_Learning

## Purpose ##

Machine Learning allows us to predict clients credit risk. In the example we used Oversampling, SMOTE, and Undersampling to show what the machine learning can do, when clients have more or less data. While loading the example we generated models that best fit the clients data, which will help the client understand the risk.

## Result ##


### Naive random oversample ###

The naive random oversample resulted in a balance score of .73, the presion score for low risk was 1.00 and the high risk is .01, with a recall score for low risk of .75 and high reisk .71

![naive oversample](https://user-images.githubusercontent.com/100543143/174501785-9d86b1f4-6360-4b87-8e58-b088430ae4d4.png)



### SMOTE oversmaple ### 

SMOTE balance score was .71, with the same presion score as Naive, but the recall scores for the low risk is .78 and high risk .63.

![smote oversampleing](https://user-images.githubusercontent.com/100543143/174501790-55093ed4-4252-4b29-be1b-068e6a16285a.png)



### Undersample ###

The undersample has balance score of .61 and the presion score is the same as SMOTE and Naive random. the recall for the low risk is .47 and high risk is .77.

![undersampling](https://user-images.githubusercontent.com/100543143/174501866-03828ef0-0848-492c-9b4a-85ef37d138e0.png)



### Combination of over and under sample ###

The combination balance score is .69 with a presion of the low risk is 1.00 and high risk .02. The recall for low risk is .87 and high risk .52

![combination over and under](https://user-images.githubusercontent.com/100543143/174501954-574c6559-748d-4fc5-8911-7b5203d02f26.png)



### Easy Ensemble ###

The Easy ensemble ada booster classifier had a balance score of .92, with low risk presion being 1.0 and high risk presion .07. The recall score for low risk is .94 and for high risk is .91

![easy ensemble ada boost](https://user-images.githubusercontent.com/100543143/174502106-f1a61b87-0a4b-49f0-8f96-520020c8bd47.png)



### Balance Random Forest Classifier ### 

The forest classifier has a balance score of .78 and a low risk presion score of 1 and high risk as .04. The recall scores are low risk .92 and high risk .66.

![balance random forest classifier](https://user-images.githubusercontent.com/100543143/174502108-46462d11-a110-4e37-a6ff-6a1bddadf54a.png)
