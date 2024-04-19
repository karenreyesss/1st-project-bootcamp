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

## Popularity of purpose for loans
Purpose of loan: This wordcloud reflects the popularity, based on the amount of users who reported the purpose of their loans, of each type of loan. 
In this case, the top five most popular reasons for getting a loan were: Debt consolidation, Credit card refinancing, Home improvement, Major purchase, and Other. 
This means most users take out loans to repay other loans they may have.

This wordcloud was created to visually determine what are the reasons why users take out loans the most.

![image](https://github.com/karenreyesss/1st-project-bootcamp/assets/159064511/c838aef9-0892-40f3-9c39-75e084aa2107)

## Number of users by State
Number of users: This is the number of users who have taken out loans. 

We wanted to determine how many users there were in each state in the US, we found that states like California and Florida have the most users in the US. 
Some further analysis may be needed to determine if there is a correlation between the hispanic population and the number of loans, do this community rely heavily on loans? 

The data from the US Census states that the top three states with the largest hispanic population are California, Texas, and Florida. 

The dataset provided did not have this information, but it might've been an interesting analysis to see how this might be related, or perhaps not at all. 

![image](https://github.com/karenreyesss/1st-project-bootcamp/assets/159064511/6af39464-afc6-4f7c-bf64-cbf5173a1c75)

## Mean annual income by state
Mean annual income: This data is the average income earned by individuals over the course of a year.
We then compared this data by each state in the US to determine where in the country is where there might be more money in the country, hoping they might be more inclined to pay up their loans; or on the contrary, this graph might be useful to see which states have the lowest mean annual income, probable meaning they may be inclined to take out loans.

![image](https://github.com/karenreyesss/1st-project-bootcamp/assets/159064511/5f09aba1-d320-4e5f-a67c-dc715a160446)

## Loan Amount by Home Ownership
Loan amount: This is the total amount given on loans
We compared this data with wether or not users own a place of their own, rent a place, or are paying a mortgage. 

We found that overall, Lending Club is more inclined to give out loans to those who are renting a place instead of those who already own their own place, which might mean that people who are renting a place might be on a tight budget, which might mean that's why they have to take out further loans. 

![image](https://github.com/karenreyesss/1st-project-bootcamp/assets/159064511/18633553-a49b-4c5f-b2bc-d48b6dbe7caf)

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
