# (Prosper Loan Dataset Exploration)
## by (Semanyoh Nissi Kekeli)


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan; including loan amount, borrower rate (or interest rate), current loan status, borrower income, employment status, listing category, loan term, prosper rating (alpha) and many other variables. It also contained some null values which have now been filled with "Unknown". Majority of the variables are numeric in nature.


## Summary of Findings

> Borrower APR is affected by the loan amount, as loan amount increases the borrower APR range becomes smaller.

> Prosper Rating has a strong effect on Borrower APR; with improving Prosper rating there is lower Borrower APR. Even as the loan amount increases, this general trend is still evident. However, when borrower with the best two Prosper ratings are taking very high loans, their APR is slightly increased. This may be to deter highly rated borrowers from taking higher loans since other plots also showed that borrowers with the best ratings generally take higher loans. It may also be that Prosper (lending company) wants to make profit since a slight increase in APR on a high loan is still very substantial.

> Another finding is that for very highly rated borrowers, their APR increases when they choose a longer loan term. However, for borrowers with ratings from HR to C, their APR reduces if they choose a longer term.

> Short term (12-month) loans are capped below 6000 dollars regardless of Prosper rating of the borrower.


## Key Insights for Presentation

> A plot showing the relationship between borrower APR and loan amount
> A distribution of borrower APR.
> A distribution of original loan amount.
> A plot showing the relationship between APR and Prosper rating.
> A plot exploring the relationship between borrower APR, prosper rating and term.
