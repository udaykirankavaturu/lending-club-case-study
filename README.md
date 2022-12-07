# Lending Club Case Study
> Lending club is an online marketplace for borrowers to seek loans and for investors to provide loans at varied interest rates.
> Given a loan dataset, the objective is to analyze the data and find patterns in the bad loans. Bad loans are the ones which have defaulted their scheduled payments and have been written off as defaulted.
> The goal of the exercise is to check for key drivers that cause loans to default, and then validate these findings on the said bad loans.
> To also provide the key findings with appropriate supporting tables/charts to explain the patterns of loan defaults.

## Table of Contents

- [Lending Club Case Study](#lending-club-case-study)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Conclusions](#conclusions)
    - [Key drivers found](#key-drivers-found)
    - [Recommendations](#recommendations)
  - [Technologies Used](#technologies-used)
  - [Contact](#contact)

## General Information

- Lending club is an online marketplace for seeking and receiving loans. Credit worthiness is a challenge as some loan applications have defaulted resulting in a financial loss for the company. The idea is to evaluate such loans and check if there are any identifiable patterns for loan default.
- The business involves two types of risks: 
  - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
  - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
  - The problem is that after loans have been sanctioned, some of the applicants have not been able to repay. So the company wants to identify and predict if a loan applicant may default before sanctioning the loans.
- The dataset used for analysis is the data of loans issued through the time period 2007 to 2011.

## Conclusions

### Key drivers found

- Lower interest rates
- Purpose of the loans
- Home ownership
- Annual income
- Revolving utilization of credit
- Debt to Income ratio
- Income source verification

### Recommendations

- care needs to be taken while providing loans to unverified income sources at lower interest rates
- debt consolidation and credit card loans seem to be high risk as they are serving to clear other loans which only increases the DTI
- verify income sources when home ownership in currently under mortgage as this loan would only add to the debt
- when annual income is less than 70000, loans have defaulted more - check loan to income ratio to decide
- revolving utilization of credit is a good measure to check likelihood of defaulting

## Technologies Used

| Library      | Version |
| ----------- | ----------- |
| pandas     |   1.5.0  |
| numpy   |  1.23.3     |
| seaborn   | 0.12.0 |
| matplotlib   | 3.6.0 |

## Contact

Created by [@udaykirankavaturu](https://github.com/udaykirankavaturu/lending-club-case-study) - feel free to contact me!

Created by [@rawatdeepesh](https://github.com/rawatdeepesh/LendingCaseStudy) - feel free to contact me!