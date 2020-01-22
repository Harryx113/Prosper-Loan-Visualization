# Prosper Loan Analysis  
The analysis utilizes a data set that contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.    
This analysis is interested in investigating the factors that affect a loan’s outcome status.
    
### Summary
From various analyses, we can get well-rounded picture of loan status with regard to our variables of interest.  
1. In the univariate analyses, we found that most loans are current or completed. Charged-offs only comprise a small portion of all the loans and defaulted loans are even more insignificant. Most borrowers own at least a home, and most loans have terms of 36 months.  
2. From the bivariate analyses, current loans have a slightly higher debt-to-loan ratio than the completed loans, implying higher risks that the current loans are bearing. Also, for the loans that are charged-off, defaulted and past due, their borrowers are less likely to be home owners.  
3. In multivariate analyses, the relationships between credit score lower range, home ownership and loan status are investigated. We found that completed loan borrowers have higher credit score lower range than all other borrowers for the home owners, but not for the ones who own no property. For the associations between original loan amount, income range and loan status, we notice that current loans generally have higher original amount. The defauted loans, on the other hand, tend to have lower original amount. As income range gets higher, the loan amount predictably gets higher.
    
### Limitations:  
1. Firstly, the outcome variable is categorical, making it difficult to generate a quantitative output using scatter plot.
2. The amount of variables (81 of them) makes it difficult to sift the variables that are crucial to the outcome variable.