# LOAN DEFAULT PREDICTOR
## INTRODUCTION
Obtaining loan to sort out pressing needs has been an important part of our daily lives both as an individual or corporate organization. Individuals and corporate organizations depend on loan to overcoming pressing financial constraints in order for them to achieve some personal and corporate goals respectively. In line with the aforementioned statement, distribution of the loans has fast became a core business part of most cooperate organizations and banks.
Distribution of loans has proven to be a very profitable business both for the lender and the borrower but at the same time it comes with a very great a risk which is referred to as “Credit risk”. This is mainly because of instance where the lender loses part, or all of the assets given out as a loan due to the fact that the borrowers was unable to repay the loans they collected. In line with this, it is imperative for banks and organizations which provide lending services to carry out rigorous verifications and validations before approving loans as this to a very large extent, helps to determine whether the applicant is credit worthy or not. 
With the recent advancements in technology and the advent of machine learning, machine learning algorithms have been widely employed to calculate and predict credit risk by evaluating individual’s historical data. This project seeks to build an automated credit scoring system which can be utilized to automatically make quick decisions on whether or not an applicant is worthy of being granted a housing loan using a partial dataset provided by Dream Housing Finance company which deals on providing home loans services. This will be implemented using Tree based machine learning classification models because of their high accuracy and ability to easily formulate statistical models quickly and effectively. Typically, loan datasets are mainly imbalanced and these can greatly affect the results of machine learning models if it’s not properly managed. This project also shows how the issue of imbalance dataset can be properly handled to build a better model.

# AIM AND OBJECTIVES
The aim of this project is to build a credit scoring system which can be utilized to automatically make quick decisions on whether or not an applicant is worthy of being granted a housing loan facility.
Objectives
•	Checking the quality of the provided data and correcting every inconsistency discovered.
•	Exploring the data to uncover key insights
•	Build models that accurately predict whether or not a loan application should be approved.
•	Optimize the performance of the models by correcting class imbalance in the target variable.
•	Compare the results from all implementations to ascertain the best model


## EXPLANATION AND PREPARATION OF DATASETS
Description of the Dataset 
The data used for this project was downloaded from Kaggle on: https://www.kaggle.com/search?q=loan+data+set. It represents a partial dataset provided by Dream Housing Finance Company which deals on providing home loans services. It contains records of customer detail provided while filling online loan application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. The data consists of 613 rows and 13 variables. 

## VARIABLE	DESCRIPTION
•	Loan_ID:	Unique identification number for each applicants record
•	Gender:	The sex of the applicant
•	Married:	Whether the applicant is married ("Yes") or not ("No").
•	Dependents:	The number of dependants an applicant has 
•	Education:	The level education of the applicant. 
•	Self_Employed:	Whether or not the applicant is self employed
•	ApplicantIncome:	The applicant Annual Income (in USD)
•	CoapplicantIncome:	The coapplicant Annual Income (in USD)
•	LoanAmount:	Total worth of the loan (in USD) for which the application was submitted.
•	Loan_Amount_Term:	The tenor of the loan in days
•	Credit_History:	Whether the applicants’ credit score is good ("1") or not ("0").
•	Property_Area:	The type of settlement were the house the applicant is apply to take on loan is located
•	Loan_Status:	Whether the loan application was approved ("Y") or not ("N")


