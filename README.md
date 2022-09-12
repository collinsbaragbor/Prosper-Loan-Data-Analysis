# Prosper Loan Data Exploration
## by Collins Baragbor


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. This data dictionary explains the variables in the data set.This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate),
current loan status, borrower income, and many others. After cleaning the dataset, it contained 75173 loans with 19 variables on each loan.
This [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) explains the variables in the data set.


## Summary of Findings

During the exploration phase, I found that the maximum APR for borrowers is in the range of 0.35 and 0.37. This could imply that many loans have average percentage rates of between 30% and 40%, which is quite high. And the lowest APR is just 2%. In the range of 0.16 and 0.20, there are some high bins. After 0.20, the number of APR values decreases, but from 0.26 to 0.30, APR rises once more. Then the data decreases and the APR count once more increases dramatically. The state with the most borrowers is California. Employed individuals received the most loans. Monthly income and loan status are negatively correlated; the lower the income, the greater the likelihood of late payments and the borrower's take huge loans. The majority of borrowers take out loans for three years, with no relationship between the loan status and term years.

The relationship between Loan Monthly Payment and Loan Amount is roughly positive. Those who take out a loan for five years pay a lot each month, making a larger loan amount and practically having outstanding credit. When borrowers request one term loan and their income is low and the repayment is largest in a year's term, they almost certainly postpone repayment and enter defaulted status because there is a negative link between monthly income and the length of the delay.


## Key Insights for Presentation

Here, I focus on the factors that could affect Loan Status. The Borrower APR, Original Loan Amount, Term, Stated Monthly Income, and Monthly Loan Payment are the key factors. I start by introducing the distribution of Loan Status followed by that of the Borrower APR and Original Loan Amount. I then go on to plot the relationship between LoanStatus, Term and StatedMonthlyIncome, MonthlyLoanPayment, LoanOriginalAmount, to see how they affect the Loan Status.