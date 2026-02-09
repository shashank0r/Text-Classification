Rough and short code for the same : www.kaggle.com/code/shashr/code1-bow

Technique used for classification: Bag of words for vectorization and logistic regression for the model


Dataset description:
Files
  train_complaints.csv - the training set
  test_complaints.csv - the test set    


  

Columns
complaint_id - id of the complaint

complaint_text - Complaint filed by the customer

primary_category - Major category of the complaint:

Credit reporting or other personal consumer reports
Mortgage
Debt collection
Credit reporting, credit repair services, or other personal consumer reports
Credit reporting
Checking or savings account
Credit card
Vehicle loan or lease
Credit card or prepaid card





secondary_category - Sub-category of the complaint

Problem with a company's investigation into an existing problem
Problem with a credit reporting company's investigation into an existing problem
Trouble during payment process
Incorrect information on credit report
Loan modification,collection,foreclosure
Incorrect information on your report
Attempts to collect debt not owed
Managing an account
Improper use of your report
Written notification about debt





severity - How urgent the complaint is

1 (Very Low): A minor inconvenience.
2 (Low): Limited impact.
3 (Medium): A repeated or frustrating friction point.
4 (High): Active financial loss or service disruption.
5 (Critical): Red Alert—Fraud, security breaches, or legal risks.
