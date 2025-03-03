# Supervised-Learning
## Sprint 8 - Surpervised Learning 
**Project Summary:** Predicted customer attrition at Beta Bank using multiple supervised learning models—including Logistic Regression, Decision Trees, and Random Forest Classifiers. **Technical Skills:** Supervised learning, logistic regression, decision trees, random forest classification, and model validation techniques. 

## Project Description

Beta Bank customers are leaving: little by little, chipping away every month. The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.

We need to predict whether a customer will leave the bank soon. I have the data on clients’ past behavior and termination of contracts with the bank.

I will build a model with the maximum possible F1 score. **I need an F1 score of at least 0.59.** I will also have to  check the F1 for the test set.

Additionally, measure the AUC-ROC metric and compare it with the F1.

## Conclusion

Based on my examination of the balance of classes and exploration of improving the quality of the model, I suggest that Beta Bank use the Random Forest Classifer model on upsampled data to predict custoner churn. The final ROC-AUC Score was 85% and the F1 came in at 0.622. 
