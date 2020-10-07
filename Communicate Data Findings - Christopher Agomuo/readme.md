# Loan Dataset Exploration
## by Christopher Agomuo


## Dataset

The Dataset gives an extensive insignt on loans of about 113,937 individuals. The information contained in this
dataset include but not limited to the following: borrower rate, monthly stated income, is borrower a homeowner, 
employment status etc. The dataset can be accessed using the link below:
https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1598155740250000&usg=AOvVaw3ofBypjV5xKP_lD_AsRyWF 
The data dictionary explaining the 81 variables can be accessed using the link below:
https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1598155740253000&usg=AOvVaw1pcI9u67QNSN85A2xbYNKX

## Summary of Findings

During the course of my exploration, I found out that most borrowers got an interest rate of approximately 0.35. In 
the same vein, in terms of prosper rating/credit grade, most borrowers scored a C as well as had a tenor of 36 months
for repayment of their laon (80,000 borrowers out of 113,937 borrowers had a tenor of 36 months). With reference to 
the logarithmic plot of the stated monthly income, most borrowers earned between $4,000-$5,000 per month. As for the 
state with the highest amount of borrowers, California topped while North Dakota had the least amount of borrowers.
The 2nd, 3rd & 4th quarter of 2013 were among the quarter with the most borrowers.

While exploring pairwise relationships, I figured out that credit grade and prosper rating had a negative interaction
with borrower rate. As regards borrower rate against employment status, those who were unemployed had the highest 
average borrower rate.There was also a slight positive relationship between borrower rate and term of the loan.
Furhter exploration of the dataset showed that a poor relationship existed between borrower rate and stated monthly
income.
In addition, borrowers who own a house had higher prosper ratings than their counterparts.

As I delved into multivariate interactions between the variables, I discovered that some borrowers don't own a home and 
earn less than $20,000 had higher interest rates on their loans. Also, retired borrowers with a loan term of 12 months 
are more likely to have low interest rates on their loans. Finally, further exploration proved that there is a 
substanstial relationship between borrow rate and those whether or not not borrow owns a home.

## Key Insights for Presentation

While executing my explanatory analysis, I polished visualization which showed the borrower rate by homeowner and 
stated monthly income. I added titles to both plots and renamed the axes labels. In addition I created a space between
the two plot to explicitly distinct them.

## References
- thispointer.com
- stackoverflow.com
- seaborn.pydata.org
- pandas.pydata.org
- matplotlib.org
- geeksforgeeks.org