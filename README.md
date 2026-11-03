# Business Understanding
Financial hardship is a condition in which an individual, household experiences difficulty meeting essential financial obligations because of insufficient resources. This can occur when income decreases, expenses increase or debt become difficult to manage. Examples could include ; difficulty paying rent, food, school fees, medical expenses etc ,significant decline in account balance, difficulty paying debts, very little or no savings amongst others.
Mobile money services, especially in developing economies like Kenya, have become an important part of everyday financial activity. Transaction records contain useful information and patterns about, income, expenditure, transfers,withdrawals, borrowing and repayment behavior, which when analyzed can provide insights on potential financial hardship in the future. 
Financial hardship is a gradual process that may or may not be detected early. This project analyses Financial hardship(Liquidity stress) as a financial condition that can potentially be indicated by changes in a person's mobile transaction patterns.

## Project Objectives
1. Assess the level of financial hardship among different age groups
2. Determine the variance in financial hardship in various regions
3. Compare the rate of financial hardship among men and women, which gender is hardly hit?
4. Examine the influence of smartphones on potential financial hardship
5. Determine the influence of earning pattern on future financial hardship
6. 
7. ## Data Mining Goals
1. To collect, organize, clean and reprocess mobile money transactions dataset
2. Identify transaction patterns associated with potential financial hardship
3. visualize data using charts and pivot tables
4. Asses the model if it met the project objectives

# Data Understanding
This data is drawn from the records of mobile money transactions for the past 6 months(m1-m6) where  m1 stands for is the most recent month while m6 stands for the oldest month. The rows contains records of 40000 mobile money users while the columns contain variables.
The independent variables include - Pay bill, Merchant pay, Send, Received, Bank Transfers Deposit, and Withdrawals.
The dependent variables include - daily average balance and liquidity stress for the next 30 days
The dataset was grouped as follows;

- **Age**
  a. <=35 "Youth"
  b. 35>=70 "Old"
  
- **Liquidity Stress**
  a. 1 "liquidty stress"
  b. 0 "no liquidity stress"

