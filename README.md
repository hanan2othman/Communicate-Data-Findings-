# Communicate-Data-Findings-
# Prosper Loan Data Exploration
## by (Hanan Othman)

## Dataset
This data set contains information on peer to peer loans facilitated by credit company Prosper. There are 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. For the purpose of this investigation we chooes Borrower Monthly Payment, Borrower Occupation, Borrower State, Borrower Employment Status , Borrower APR, Prosper Score, Loan Amount .
The dataset can be found in this link:  https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv

## Key Insights for Presentation

1-  Most of the loans in the data set are actually current loans. Past due loans are split in several groups based on the length of payment delay. Other big part is completed loans, defaulted loans compromise a minority, however chargedoff loans also comporomise a substanial amount.

2- The majority of borrowers are employed and all other categories as small part of borrowers. In small Group full time has highest, after that self empolyed are there and so on.

3-The highest borrowers quantity is from CA (California ) and in TX , NY , FL (Texas , New York , Florida ) has almost same no. of borrowers .

4- With a boundary of mean and 3 times standard deviations distribution of monthly income still has noticeable right skew but now we can see that mode is about 5000.

5- The highest median of monthly paid income is of A , followed by AA and B.

6-In both of the Graphs the debt Consolidation have most frequency among all of them.

7- The highest borrower APR are again for Non -Employed and it is followed by borrowers with income range ($1-24,999).
The lowest borrower rate is of income range ($100,000)

8- The highest borrower rate is for Currenttly Acive Loans and follwed by Completed Loans

9-LoanOriginalAmount and BorrowerAPR is having negative relationship, BorrowerAPR and LenderYield is having strong positive relationship, ProsperScore and BorrowerAPR is having Negative relationship, LoanOriginalAmount and MonthlyLoanPayment is having strong positive relationship.

10- the Completed Loan are the lowest .The Currently Active loans are highest and the  Self - Employed are largest.

11- Except for the lowest ratings defaulted credits tend to be larger than completed. Most of the defaulted credits comes from individuals with low Prosper rating.


**Why this project?** 
Data visualization is an important skill that is used in many parts of the data analysis process. Exploratory data visualization generally occurs during and after the data wrangling process, and is the main method that you will use to understand the patterns and relationships present in your data. This understanding will help you approach any statistical analyses and will help you build conclusions and findings. This process might also illuminate additional data cleaning tasks to be performed. Explanatory data visualization techniques are used after generating your findings, and are used to help communicate your results to others. Understanding design considerations will make sure that your message is clear and effective. In addition to being a good producer of visualizations, going through this project will also help you be a good consumer of visualizations that are presented to you by others.


## Summary of Findings
 Most of the loans in the data set are actually current loans. Past due loans are split in several groups based on the length of payment delay. Other big part is completed loans, defaulted loans compromise a minority, however chargedoff loans also comporomise a substanial amount.

The majority of borrowers are employed and all other categories as small part of borrowers. In small Group full time has highest, after that self empolyed are there and so on.

The highest borrower rate is for Currenttly Acive Loans and follwed by Completed Loans

LoanOriginalAmount and BorrowerAPR is having negative relationship, BorrowerAPR and LenderYield is having strong positive relationship, ProsperScore and BorrowerAPR is having Negative relationship, LoanOriginalAmount and MonthlyLoanPayment is having strong positive relationship.

Except for the lowest ratings defaulted credits tend to be larger than completed. Most of the defaulted credits comes from individuals with low Prosper rating.
 


### Licensing, Authors, Acknowledgements
Must give credit to Udacity for the data. You can find the Licensing for the data and other descriptive information at the Udacity Website.
