# Loan-Analysis-of-Lending-Club
Data Exploration of loan data using univariate, bivariate and multivariate data analysis

## summary
Prosper is an Internet P2P lending financing company that provides investors and lenders with a trading platform and then draws fees to make a profit. In this visualization project, we will see the annual average annual loan earnings in the visualization. Rate, and the average annual rate of return of funders who invest in annual income at various stages.

## design
There are a total of 81 variables in the dataset. This dataset contains complete loan data for all loans issued through 2005-2014, including the current loan status (Current, Late, Fully Paid, etc.) and latest payment information. The file is a matrix of about 113 thousand observations and 81 variables. A data dictionary is provided in a separate file.

## Feedback
1. The ordinate does not indicate what the range of data is.
2. With the year as the selection condition, the loan interest rate of the lender showing the income of the same year will be more intuitive.

## Findings
- The distribution of interest rate looks normal except an odd pick around 0.32.
- Monthly income includes many outlier and the distribution shows a single column which should be changed with log scale.
- Loan amount is right skewed which if we use log scale we end up with normally look distribution with picks on some specefic values.
- Debt to income ration is not the best measure to estimate the interest rate or decide on the loan amount.
- There is an opposite relation between the lenders rating and the interest rate; where highly rated lenders receive low interest rate loans.

## Resource
https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv

https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554172027131000
