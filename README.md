# Project Name
> EDA-Lending-Case-Study



## Table of Contents of PDF file attached.
- Problem Statement
- Objectives
- Loan Data
- Data Cleaning
- Data standardization
- Segmentation
- Univariage analysis
- Bivariate Analysis
- Correlation 
- Summary.

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem Statement
    You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
        If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
        If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
    The data in “loan.csv” contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, 

- Objectives
    - Using Exploratory Data Analysis we need to understand how consumer attributes and loan attributes influence the tendency of default.
    - When a person applies for a loan, there are two types of decisions that could be taken by the company:
        1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
            Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
            Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
            Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
        2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
    



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Lower the income group having higher percentage of charged off.
- Interest rate above 12% is having higher percentage of Charged off
- Small business and renewable energy loans having higher percentage of charged off.
- The loan distributed in 2011 and Dec month having higher percentage of charged off.
- G and F grade customers having higher percentage of charged off.
- Customers who are having higher number of public record bankruptcies having higher percentage of charged off.
- Customers having above 15% total montly monthly debts payment having higher percentage of charged off.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python Libraries pandas, seaborn and matplotlib.pyplot
- Jupyter notebook 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad and IIT Bangalore.
- This project was based on https://learn.upgrad.com/ Exploratory Data Analysis.


## Contact
Created by [@settumurugan] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->