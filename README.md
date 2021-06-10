PROBLEM STATEMENT:
  Fraud detection involves monitoring the activities of 
populations of users in order to estimate, perceive or avoid 
objectionable behaviour, which consist of fraud, intrusion, and 
defaulting. This is a very relevant problem that demands the 
attention of communities such as machine learning and data 
science where the solution to this problem can be automated.
  
  This problem is particularly challenging from the perspective of 
learning, as it is characterized by various factors such as class 
imbalance. The number of valid transactions far outnumber 
fraudulent ones. Also, the transaction patterns often change 
their statistical properties over the course of time

INTRODUCTION:
  It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. This data set presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the data set The feature 'Amount' is the transaction Amount, this feature can be used for example-dependent cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise

SOLTION STATEMENT:
With ever-increasing online transactions and production of a 
large volume of customer data, machine learning has been 
increasingly seen as an effective tool to detect and counter 
frauds. However, there is no specific tool, the silver bullet, 
that works for all kinds of fraud detection problems in every 
single industry. The nature of the problem is different in every case and every industry. Therefore every solution is 
carefully tailored within the domain of each industry.

In machine learning, parlance fraud detection is generally 
treated as a supervised classification problem, where 
observations are classified as “fraud” or “non-fraud” based 
on the features in those observations

CONCLUSION:
BY doing K-nearst algorithm we can conclude that While the algorithm does reach over 99.8% accuracy, its precision remains only at 28% when a tenth of the data set is taken into consideration

Fraud detection is based on Hidden Markov Model Which is learning algorithm , hence not 100% correct

It has detected those transaction as fraud where user belongs to low category  and high category payment is made or vice versa

The mechanism require at least 10 transaction to determine accurately the transaction as fraud or not.
