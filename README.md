# Credit-Card-Approval-Prediction-Project
This project aims to predict credit card approval using machine learning. Data is collected from various sources including applicant information and financial records. After preprocessing the data, machine learning models are trained and evaluated. The best-performing model is deployed for real-time prediction. Ongoing monitoring ensures the model's effectiveness and reliability.

The credit card approval system successfully providing a reliable and consistent method for assessing applicants' creditworthiness.By comparing all the models the **Random Forest algorithm** is perfoming good and the accuarcy is 0.79 Even though the XGBoost classifier is giving good Accuracy we go with RandomForest Classifier,Because the Recall and F1-score,although The model is making some errors, with 11 instances of false positives and 3 instances of false negatives there is no overfitting,it is performing good and maintaing consistancy with the different data splits but other models making overfitting while in the cross validation.So we accept the null hypothesis.The RandomForestClassifier is performing good and efficiency in predicting whether an applicant should be approved for a credit card.

COMPARISON AMONG THE MODELS

![Comparison of models](https://github.com/VaishnaviKenche4/Credit-Card-Approval-Prediction-Project/assets/159226103/06200837-56e6-42b9-a9b1-203cef0f9b7a)


ROC CURVE for RandomForest

![ROC curve](https://github.com/VaishnaviKenche4/Credit-Card-Approval-Prediction-Project/assets/159226103/44a27907-0090-4b35-bc38-53eb7592be1e)

