# Loans Data Exploration

## Dataset Overview
This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income among many others. I have only Extracted 30 variables out of the original dataframe for easier analysis and visualization.

## Investigation Overview
The main focus of this investigation is to identify the different factors that could have an impact on the outcome of the loan as well as the loan interest rate. I have examined several of these factors including the borrowers monthly income, the loan origianl amount among other variables.

## Summary of Exploration
1. approximately one third of all loans' payments have been completed, while about 50% of them are still current.
2. Debt consolidation is by far the most common reason borrowers take loans.
3. There is a strong positive linear relationship between the loan interest and the lender yield which is to be expected.
4. Borrowers who has taken loans with less interest rates have either completed their payments or their loan is still currents with no payments are past due. loans with higher interest rates, however, have either been charged off or defaulted.
5. Borrowers with a higher monthly income have either completed their loans' payments or their loans are still currents with no missed payments. Borrowers with lower monthly income on the other hand have failed to keep up with thir loan payments.
6. Borrowers with less current delinquencies were more able to complete their loans or to keep up with their payments. In contrast, borrowers with higher delinquencies couldn't complete their loans' payments.
7. Borrowers with a higher prosper score get loans with a lower interest rates which in turn results in a lower lender yield.
8. The average loan amounts have increased over the time period in the data set from around 4000 dollars in 2005 to over 11000 dollars in 2014.

## Key Insights for Presentation
For the presentation, I mainly focused on the different factors that could have an effect on the loan status as well as the loan interest rate.
I began by depicting the distribution of several variables including the loan status, borrower rate and lender yield.
This was followed by a series of bivariate visualization that depict the relationship between different variables that show a significant correlation including Borrower Rate vs lender yield, borrower rate vs average loan amount, and loan status vs borrower rate.
After than I move into the multivariate visualization where I depict the relationship between the borrower rate and lender yield faceted by the prosper rating.
At the end, I show the change of loan amounts over the time period in the dataset.