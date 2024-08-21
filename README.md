# Lending Club Case Study

## Problem Statement - ## General Information
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

We are going to use loan.csv as a dataset for our analysis.

## Objective
Use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

## Constraints
When a person applies for a loan, there are two types of decisions that could be taken by the company:

A. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

	1. Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

	2. Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

	3. Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

B. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Summary
Following files has been inlcluded as a part of solutions:
1. READ.me file for Problem discriptions.
2. Lending Club Case Study.ipynb ipython file for performing EDA.
3. Loan.csv file which is the dataset we are using for EDA.
4. Data_Dictionary.xlsx is data dictionary which describes the meaning of the variables.
5. Lending Club Case Study.pdf is the presentation of the analysis done as a part of EDA and the conclusion.
 
## Collaborators
1. Ravi Theja 
2. Bhushan Pande