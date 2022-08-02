# Prosper Loan Data Exploration
## by Alex Kakai


## Dataset

> This data set contains loans data from Prosper, an America’s first marketplace lending platform, with more 9 billion dollars in disbursed loans. The dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, borrower employment status, borrower credit  history, latest payment information and many others.


## Summary of Findings

> Distribution of Home Owners is almost equally shared, Home Owners are slightly the majority with 53.2% while None Homers Owners are at 46.8%.

> Majority of the loans have a loan term of 36 months followed by 60 months and lastly very few are of 12 months.

> Majority of the customers disbersed to are either employed or are in full time employement.

> Majority of clients took the loans so that they can consolidate their debts, improve their homes and for business purposes.

> Small Loan and monthly payments amounts are subjected to high interest rates as compared to big loan and high monthly payments amounts. From the plots majority of the loans fall in the 5000 dollars bracket while the monthly payments fall between 100 and 200 dollars, however, on the intereest rates, these two fall to right which is towards the maximum interest rate applied.

> MonthlyLoanPayment and LoanOriginalAmount have the same relationship when compared with the various interest rates variables (BorrowerRate/BorrowerAPR/LenderYield). These two variables are negatively correlated with the interest rate variables, as MonthlyLoanPayment and LoanOriginalAmount increase BorrowerRate/BorrowerAPR/LenderYield descrease.

> Relationship between LoanOriginalAmount and LoanTerm shows that loans size is directly proportinal to loan term. Smaller loan amounts have shorter terms as compared to larger loan amounts which have longer repayment period.

> Relationship between MonthlyLoanPayment and LoanTerm shows a different trend as compared to Original Loan Amount, Loans with 36 months have generally a lower average monthly loan payment amount (below 200 dollars) as compared to the other two loan terms. Loans with 60 months repayment plan have the highest average monthly loan payment amount of about 300 dollars while 12 months loans is around 250 dollars

> Loan Term behaves different with the interest rates, we observe for BorrowerRate and LenderYield, there is an increase in the rates with increase in number of months. However, for BorrowerAPR, the loans have the same average of around 20% across the three loan terms.

> For short term loans (12months) there is no significant difference between home owners and non home owners on the average loan amount given out, however, this changes for 36 months and the margin increases for 60 months loan term where there is a significant difference with home owners being preferred over non home owners.

> Loans with long repayment terms have low average monthly repayments as compared short term loans which seem to have huge average monthly repayments. Short term loans of 12 months have a steeper graph as compared to 36 months loans whose graph is less steep. 60 months loans have a fairer graph which is less steep of the three repayment terms depicting lower repayment amounts.

> Clients with short term loans that have bigger monthly repayment amounts seem to struggle with repayments. We observe loans which are past due with 1-15 days and 16-30 days only short term loans are the ones with a bigger percentage, the standard deviation from the mean is quite big compared to the other loan term brackets.

> Loan Size is majorly affected by the monthly loan payment with a correlation value of 0.84, other factors that impact loan size are: loan term, StatedMonthlyIncome, CreditSCoreRangeLower and CreditSCoreRangeUpper. The three interest rate variables (BorrowerAPR, BorrowerRate,LenderYield), ListingCatergory and AmountDelinquient negatively impact the loan amount to be disbursed.


## Key Insights for Presentation

> Prospers targets majorly clients that are employed or in full time employed, majority of their clients have at least an income.

> Home owners have a slight edge against none home owners, for loans with longer repayment terms, home owners get averagely 2000 dollars more than non home owners.

> Its cheaper to take bigger loans with long repayment plan as compared to shorter loans with short repayment plans which are quite expensive because higher interest rates are applied.

> Clients taking bigger loans prefer longer payment plans while smaller loans they prefer short repayment plans.

> Monthly repayment amounts for shorter loans are almost equal to bigger loans, this is because shorter loans have to repay bigger amounts to offset the loan while at the same time big loan clients even though have a longer repaint plan, have to make slightly higher amounts due to the huge loan amounts they took.
