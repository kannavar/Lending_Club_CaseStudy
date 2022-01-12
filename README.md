# Project Name
> Exploratory Data Analysis on Lending Club Case Study 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

Lending Club Case study is mainly about understanding of risk analytics area in banking and financial services. The goal of this project is to perform Exploratory Data Analysis on the given dataset and derive insights on the risk profile when lending to different types of customers.

**- What is the background of your project?**

Lending Club is a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 

There are two types of risks that are associated with the bank’s decision:

If the applicant is **likely to repay the loan**, then not approving the loan results in a **"loss of business"** to the company

If the applicant is not likely to repay the loan, i.e. he/she is **likely to default**, then approving the loan may lead to a **"financial loss"** for the company


**- What is the business probem that your project is trying to solve?**

The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate. 

We will use EDA to understand how **consumer attributes** and **loan attributes** influence the tendency of default.

**- What is the dataset that is being used?**

loan.csv - This dataset contains the complete loan data for all loans issued through the time period 2007 to 2011 and whether a particular loan is defaulted or not 

Data_Dictionary.xlx  - This spreadsheet contains the description of all the variables (columns) present in the loan dataset.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- A total of 16% of loans issued by lending club got defaulted(charged_off)

<b>Avoid </b>

- Lending Club issueing majority of loans without Veritication which should be avoided to reduce defaults.
- Higher the Loan amount the more is chance of default and recoveries.
- Lending club should avoid lending to people with above 50% revolv_credit_utilisation
- Lending at higher interest rates increases the chance of loan default and lending at interest rate above 14% can be reduced
- Debt to Income ration of the borrower should preferably be <= 15 , Increasing debt to income ratio is leading to higher defaults
- Loans should preferably be not given to people with Publich Insolvency Records
 
<b>Caution</b> 

- Loan grades B , C , D should undergo extra scrutiny for following subgrades in the order B5 , B3, B4 , C1 , C2
- Loan defaults are higher for 10+ years experience and freshers with 0 years experience. We should moderate lending to 10+ years of experience.
- Loans issued in last quarter of the year have higher chance of defaults compared to other months. One inference could be to meet the year end targets loans are issued at faster pace with easier approvals

<b>For</b>

- Chance of default keeps decreasing with increase of Employee Annual Income

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Python 3.8.8
- Numpy - version 1.20.1
- Pandas - version 1.2.4
- matplotlib - version 3.3.4
- seaborn - vesion 0.11.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- Our Professor S.Anand of Gramener for teaching EDA in beautiful way

## Contact
Created by [@kannavar] - feel free to contact me!
