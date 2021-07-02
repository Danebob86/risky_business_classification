# Unit 11 - Risky Business

![Credit card fraudster](https://flxt.tmsimg.com/assets/p6984_p_v10_ae.jpg)

## Background
Mortgages, student and auto loans, and debt consolidation are just a few examples of credit and loans that people seek online. Peer-to-peer lending services such as Loans Canada and Mogo let investors loan people money without using a bank. However, because investors always want to mitigate risk, a client has asked that you help them predict credit risk with machine learning techniques.
In this assignment you will build and evaluate several machine learning models to predict credit risk using data you'd typically see from peer-to-peer lending services. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so you will need to employ different techniques for training and evaluating models with imbalanced classes. You will use the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:

# Resampling
Use the imbalanced learn library to resample the LendingClub data and build and evaluate logistic regression classifiers using the resampled data.

## Questions
1. Which model had the best balanced accuracy score?
2. Which model had the best recall score?
3. Which model had the best geometric mean score?

## Answers
1. SMOTE model has best balacned accuracy score 0.993678
2. SMOTE & SMOOTEEN model has best recall score at 0.99
3. All models have a geometric mean of 0.99

# Ensemble Learning
In this section, you will train and compare two different ensemble classifiers to predict loan risk and evaluate each model. You will use the Balanced Random Forest Classifier and the Easy Ensemble Classifier. Refer to the documentation for each of these to read about the models and see examples of the code.

## Questions
1. Which model had the best balanced accuracy score?
2. Which model had the best recall score?
3. Which model had the best geometric mean score?
4. What are the top three features?

## Answers
1. The Easy Emsemble had a higer score of accuracy score of 0.93 vs. 0.77
2. The Easy Emsemble had a higer recall score of .95 vs. 0.90
3. The Easy Emsemble had a higer geometric mean score of .93 vs. 0.77
4. top three features are:
    1. total_rec_prncp
    2. total_pymnt_inv
    3. last_pymnt_amnt
