# Project Name
> Lending Club Case Study.
>> EDA


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

Lending Club largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

We have been provided with complete loan data for all loans issued through the time period 2007 to 2011. Using this data, we need to infer details or strong factors which contributes to loan default. This can inturn help Lending Club minimise the risk of losing money while lending to customers.

## Conclusions

Based on our Exploratory Data Analysis on the dataset, the below are the strong indicators that contribute for loan default.

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
- Pandas - version 1.4.2
- Numpy - version 1.21.5
- Matplotlib - version 3.5.1
- Seaborn - version 0.11.2
- plotly - version: 5.6.0

## Acknowledgements
- Upgrad Study Materials

## Contact
Created by [@elcommselva & @rajaanr7] - feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
