# 1st-project-bootcamp
First group project for Data Analytics Bootcamp

## Introduction
As the dedicated team supporting the Chief Operating Officer (COO), our main goal is to explore the nuances of loan distribution across different segments within our enterprise. From understanding borrower profiles to evaluating loan performance in search of valuable insights essential for strategic decision-making. 

## ¿What is Lending Club?
LendingClub is a peer-to-peer lending company, headquartered in San Francisco, California. It is the leading digital marketplace bank in the U.S., connecting borrowers with investors since 2007. 
Lending Club enables borrowers to create unsecured personal loans between $1,000 and $40,000. The standard loan period is three years. Investors can search and browse the loan listings and select loans that they want to invest in based on the information supplied about the borrower, amount of loan, loan grade, and loan purpose. Investors make money from interest. Lending Club makes money by charging borrowers an origination fee and investors a service fee.

## What can we tell from our dataset?
With over 750,000 loans registered in this data set, we had access to complete loan data from 2016 to 1017, including the current loan status (Current, Late, Fully Paid, etc.), “-----” and latest payment information.

## Insights from Lending Club Data
Is there any trend of opportunity based on demographic or socioeconomic data? 
How many users are there in each state? Popularity of each loan purpose, mean annual income in each state, loan amount by homeownership?
Are there factors that help to have a revenue growth model with lower risk of increasing revenue?
What’s an approach to risk assessment and product categorization based on loan grades and sub-grades.

## Demographic Analysis



## Loan Amount by Home Ownership

## Total Interest Received by Product
Debt Consolidation: This category has the highest total interest received, indicating that it’s the most profitable loan purpose for Lending Club. (over $700 million US dollars)
Credit Card Refinancing and Home improvement display the subsequent most profitable products for Lending Club. ($222 million and $76 million US dollars respectively)
Vacation and Green Loan: These categories have the shortest bars, suggesting they generate the least amount of interest. ($3.5 million and $570,000 dollars respectively)

![Total_Int_Rec_by_Title](https://github.com/karenreyesss/1st-project-bootcamp/assets/151306990/d9932329-550a-44b1-8b0c-d2c7407a0ddd)

## Top Products by Grade

Debt Consolidation: This appears to be the largest category across all charts, indicating that most people are using these loans to consolidate their debts.
Credit Card Refinancing: This is also a significant portion but smaller than debt consolidation, suggesting a substantial number of people are using these loans to refinance their credit cards.
Home Improvement and Business: These categories occupy smaller sections of the pie charts, indicating fewer people are using the loans for these purposes.
Other: The size of this category varies slightly across different charts, suggesting it includes a variety of other loan purposes.

![image](https://github.com/karenreyesss/1st-project-bootcamp/assets/151306990/c66d7fb9-58a4-4668-a7e3-3d7fc03eba4c)


## Average Loan Count by Grade and Sub-Grade
We are able to observe the distribution of loans given to customers based on their credit grade at Lending Club.
From this graphs, we can infer that Lending Club issues the majority of its loans to customers with ‘B’ and ‘C’ credit ratings. This could suggest that their risk tolerance is balanced between high creditworthy customers (Grade ‘A’) and those with a bit more risk (Grades ‘B’ and ‘C’). The significantly fewer loans issued to customers with lower credit ratings (‘E’, ‘F’, and ‘G’) indicate a lower risk appetite for these grades. 

![Average_Loan_Count_by_Grade](https://github.com/karenreyesss/1st-project-bootcamp/assets/151306990/0d8e7e22-7c9b-4ef4-99d6-0680b5b737fc)
![Average_Loan_Count_by_Sub_Grade](https://github.com/karenreyesss/1st-project-bootcamp/assets/151306990/0ca7c59b-c915-4bb6-9d51-0795a7711952)


## Distribution of Interest Rate

## Distribution of products within Grades and Sub-Grades

Debt Consolidation and Credit Card Refinancing: These titles appear to have the highest counts across all grades, indicating that they are the most common purposes for loans across all credit grades. (417,193 and 152, 48 loans respectively in total) 
Home Improvement: This title also appears frequently across all grades, summing 55,898 loans in total.
Other Titles: The remaining titles (such as Vacation, Green loan, Home buying/relocating, Moving and relocation, Car financing, Medical expenses, Major purchases, Businesses, Other) have varying counts across different grades. Being the most prominent "Major purchase" (17,939 loans), "Medical expenses", (10,128 loans), and "Car financing" (8,589 loans).

Regardless of the credit grade, most of Lending Club’s loans are used for Credit Card Refinancing and Debt Consolidation. Suggesting these are the most common financial needs of Lending Club’s customers across all credit grades. 

![Distribution_of_Titles_within_each_grade](https://github.com/karenreyesss/1st-project-bootcamp/assets/151306990/026416f0-f7c2-48d1-a989-2978bd519fa2)
![Distribution_of_Titles_within_each_sub_grade](https://github.com/karenreyesss/1st-project-bootcamp/assets/151306990/5de07a8e-e64d-485d-a0ed-08afe8a395a5)

## Average Risk Metric for each product

These values represent the average risk metric for each loan purpose, which is calculated based on factors like accounts now delinquent, delinquencies in the past two years, and late loan status.
![Average_Risk_Metric_for_Each_Title](https://github.com/karenreyesss/1st-project-bootcamp/assets/151306990/0e29ff4e-2e36-4d05-a440-c1deaa35a608)
