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
The patterns included Volume, total volume and highest amount.
The dataset was grouped as follows;

- **Age**
  a. <=35 "Youth"
  b. 35>=70 "Old"
  
- **Liquidity Stress**
  a. 1 "liquidty stress"
  b. 0 "no liquidity stress"

  # Data Preparation
  -  I checked for Duplicate records, spelling differences, data distribution, ensuring its one record per row, one variable per column, no blanks in the middle of my dataset, headings are kept in row 1
  - I grouped the data according to age and liquidity stress
  - I sorted the data according to age from the highest to the smallest

  # Modelling
  a. Pivot Tables
  b. Charts
  
  The **findings** were as follows:
  
  1. The following patterns were associated with potential liquidity stress; volume, total value and highest amount
  2. The female gender had the highest sum of liquidity stress as opposed to the male users
  3. The old had a higher sum of liquidity stress as opposed to the youthful generation
  4. The users from the Coastal and Eastern corridor were the most hit by financial hardship as opposed to other regions while the  Islanders were the least hit
  5. The smartphone users have a higher sum of liquidity stress as opposed to non-smartphone users
 
  6. <img width="637" height="320" alt="Screenshot 2026-11-03 090617" src="https://github.com/user-attachments/assets/f8b96069-5c3e-4921-93d6-ba546744c5c2" />
      <img width="837" height="325" alt="Screenshot 2026-11-03 090724" src="https://github.com/user-attachments/assets/ceb5fc38-f214-4905-a3d4-7ffb9de55dde" />
      <img width="701" height="381" alt="Screenshot 2026-11-03 090801" src="https://github.com/user-attachments/assets/49bf8f4d-db27-423b-9ae2-0832ee7475f5" />
      <img width="763" height="365" alt="Screenshot 2026-11-03 090844" src="https://github.com/user-attachments/assets/91251995-3c42-4e22-964f-f287c2e43673" />
      <img width="634" height="362" alt="Screenshot 2026-11-03 090927" src="https://github.com/user-attachments/assets/fdf119b0-6063-4005-b041-37ef3cd8c86c" />

   # Evaluation
  
 1. The model identified mobile money transaction patterns associated with potential financial hardship
 2. The model compared the level of liquidity stress among the female and male, old and the youthful generation
 3. The model determined the variance, per region, of financial hardship based on mobile money transaction records
 4. The model organized, cleaned and reprocessed the dataset for analysis
 5. The model visualized the data using charts
 6. 
    **Conclusion**
    The model was effective in achieving the project objectives and data mining goals.
    
The project therefore offers the following **reccommendations**

1. Financial literacy programs for users showing persistent risk indicators
2. Responsible lending practices to avoid increasing debt burden
3. Personalized financial guidance based on transaction patterns
4. Budgeting and savings support for users experiencing declining ballances

5. ## Challenges
6. 1. High cost of internet to access data
7. 2. Limited data sources
      

# Deployment
This information can be accessed via https://github.com/Datamegke
## contact
For any feedback please contact via
1. **Email**:meg858477@gmail.com
2. **Phone number**:+254 743103223

## Licence
   MIT licence has been applied to this project
   
## Collaborators
1. Mary Margaret


     

      




  

