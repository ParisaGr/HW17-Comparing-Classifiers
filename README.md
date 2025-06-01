#Comparing Classifier
## Objective:
The objective of this work is to build a predictive model that helps the bank identify clients who are most likely to subscribe to a term deposit, so that marketing resources can be focused on those clients, improving campaign effectiveness and reducing wasted effort. 
Predicting whether a bank client will subscribe to a term deposit (i.e., open a long-term deposit account) based on their demographic, financial, and contact information. This is important for the bank because:
- Term deposits are valuable products that provide stable funding for the bank.
- Marketing campaigns (such as phone calls) are costly and time-consuming.
By accurately predicting which clients are most likely to subscribe, the bank can target its marketing efforts more efficiently, reducing costs and increasing the success rate of its campaigns.

This work compared the performance of the classifiers (k-nearest neighbors, logistic regression, decision trees, and support vector machines), finding the most effective model for prediction.
Comparing classifiers ensures the bank uses the most effective, efficient, and business-appropriate model to target clients for term deposit marketing, directly supporting the business objective of maximizing campaign success and minimizing wasted effort.

The dataset comes from the UC Irvine Machine Learning Repository (https://archive.ics.uci.edu/dataset/222/bank+marketing). The data is from a Portuguese banking institution and is a collection of the results of multiple marketing campaigns.


## Findings
Below is the finding:
- Logistic Regression and Linear SVM are the best choices
- Logistic Regression and Linear SVM have high precision (~0.70), meaning when they predict a client will subscribe, they are often correct.
- All models have high accuracy (close to 0.90)
- All models have low recall (~0.26–0.34)
- All models have modest F1-scores (0.35–0.40)
- All models train fast, even with a larger subset
- Decision Tree has great train accuracy (0.9998) but low test accuracy (0.845), due to overfitting

## Next steps and recommendations
Try class balancing techniques (e.g., SMOTE). Synthetic Minority Over-sampling Technique (SMOTE) creates new, synthetic samples by interpolating between existing minority class samples. This can help to reduce overfitting.
