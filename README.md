# hackathon-NBFC-loan-default
Data Science Hackathon to predict loan default

## Description
A non-banking financial institution (NBFI) or non-bank financial company (NBFC) is a Financial Institution that does not have a full banking license or is not supervised by a national or international banking regulatory agency. NBFC facilitates bank-related financial services, such as investment, risk pooling, contractual savings, and market brokering.
The following is the story of a challenge faced by DHDL Ltd. (Name Changed), an NBFC in India. In recent times, the company is struggling to mark profits due to an increase in Loan Defaults. The company aims to determine the relative importance of each parameter with regards to their contribution as to whether a loan is going to default or not. Provided is a sample that contains the data of 90,000 + clients who have taken a loan from the company in the past with the information on whether the loan defaulted. 
The objective of this exercise is to understand which parameters play an important role in determining whether a client will default on the loan payment or not

## Objective
The goal of the problem is to predict whether a client will default on the loan payment or not. For each ID in the test_data, you must predict the “default” level.

### Data Dictionary

|Labels|Description|
|:-----|:----------|
|ID|unique ID assigned to each applicant|
|loan_amnt|loan amount ($) applied each applicant|
|loan_term|Loan duration in years|
|interest_rate|Applicable interest rate on Loan in %|
|loan_grade|Loan Grade Assigned by the bank|
|loan_subgrade|Loan SubGrade Assigned by the bank|
|job_experience|Number of years job experience| 
|home_ownership|Status of House Ownership|
|annual_income|Annual income of the applicant|
|income_verification_status|Status of Income verification by the bank|
|loan_purpose|Purpose of loan|
|state_code|State code of the applicant's residence|
|debt_to_income|Ratio to total debt to income (total debt might include other loan aswell)|
|delinq_2yrs|number of 30+ days delinquency in past 2 years|
|public_records|number of legal cases against the applicant|
|revolving_balance|total credit revolving balance|
|total_acc|total number of credit lines available in members credit line|
|interest_receive|total interest received by the bank on the loan|
|application_type|Whether the applicant has applied the loan by creating individuall or joint account|
|last_week_pay|How many months have the applicant paid the loan EMI already|
|total_current_balance|total current balance of all the accounts of applicant|
|total_revolving_limit|total revolving credit limit|
|default|status of loan amount, 1 = Defaulter, 0 = Non Defaulters|
