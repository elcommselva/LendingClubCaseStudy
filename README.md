# Project Name
> Lending Club Case Study.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

Lending Club largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

We have been provided with complete loan data for all loans issued through the time period 2007 to 2011. Using this data, we need to infer details or strong factors which contributes to loan default. This can inturn help Lending Club minimise the risk of losing money while lending to customers.

## Conclusions

Based on the data following are the strong indicators that contribute for loan default.

1. 'purpose' of the loan 
    - loans procured for "small business" are more prone towards chargeoff/default
2. 'int_rate' interest rate
    - loans with higher interest rate in combination with 'grade' like F & G (or)
    - loans with higher interest rate in combination longer duration of term
    are likely to default
3. 'grade' Grading of the borrower
    - Customers with Grade F & G are high risk customers and there are very high chances of charge off
4. 'dti' Debt to Income
    - Debt to Income ratio is directly proporsational to the Charged off or default
5. 'addr_state' State
    - People from geographical regions state: NV & FL are likely to default more


## Technologies Used
- Pandas - version 0.24.2
- Matplotlib - version 3.0.3
- Seaborn - version 0.9.0
- Numpy - version 1.16.2

## Acknowledgements
- Upgrad Study Materials

## Contact
Created by [@elcommselva & @rajaanr7] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->