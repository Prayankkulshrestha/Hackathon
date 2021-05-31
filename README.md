# Hackathon

Problem Statement:
Happy Customer Bank is a mid-sized private bank that deals in all kinds of banking products, like Savings accounts, Current accounts, investment products, credit products, among other offerings.The bank also cross-sells products to its existing customers and to do so they use different kinds of communication like tele-calling, e-mails, recommendations on net banking, mobile banking, etc. In this case, the Happy Customer Bank wants to cross sell its credit cards to its existing customers. The bank has identified a set of customers that are eligible for taking these credit cards.

# intial Data Observations

1. Data has only Continous variable
2. Credit variable has Null value
3. Data has both Demographics as well sale variables


# Data Cleaning
1. Consider null values as other class


# Feature Engineering
1. Create Sales Feature by combing region code and channel code
2. Creare Demographic variable by combining Occuption & Gender
3. Extract Vintage month & year information
4. Count the various feature like gender etc
5. Bin the Age and Anuual avg balance
6. Agg various feature on different level
7. Label Encoding & StandardScaling 


# modelling
1. Start with Randomforest baseling with score around 0.63 (without feature engineering)
2. Use Light grident boosting with score 0.78 (with label encoding & standardscaling)
3. Read the previous work & optimize the LGBM & XGboost & Catboost
4. use above model & use weighted voting classification as final solution

Close the Hackathon as 266 Public Leaderboard & 41 rank on private Leaderboard out of 8300 candidate
