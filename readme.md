# (Prosper Laon Data)
## by (Mahmoud Wasfy)


## Dataset

> The Prosper Laon Data includes around 114,000 rows, each row represents a loans between the year 2005 and 2014. We investigated the interactions between features such as the Loan Amount, income ranges, loan status, Term of payment and Employment status for the borrower, and a lot more features has been explored and plotted. We utilized some data cleaning and tidiness to the data as required to reach the below mentioned findings. 


## Summary of Findings

> 1- It is observed that most loans are paid over a duration of 36 Months and some of them are 60 Months and only few loans are paid back on 12 Months. It is not clear why there is no loans on 24 Months!?

> 2- most of the loans are still running as current loans followed by the completed loans. The data is right skewed and it seems that defaulted and past due loans are smaller numbers.

> 3- The intrest rate varies from 0 to around 0.38% with a spike in loans with intrest above 0.3% but what affects the intrest rate? Is it related to other features in the dataset? 

> 4- Although the description of the variable (ProsperScore) shows that the values should range between 1 & 10 it is noticed that there are some rows showing a values of 11. It is not clear if this is a wrong inputs in data or it represents something that is not explained in the description. In all cases the data shows a bell shaped curve with spikes at risk scores of 4, 6, 8.

> 5- most of the loans in the dataset seems to be due to 'Debt Consolidation' followed by 'Home Improvement' and 'Business Loans' 

> 6- As expected most of the loans goes to employed / full time and few only goes to Not employed and retired individuals. 

> 7- Home Owners and Non-home-owners are almost equal in numbers, but does this affect the intrest rate they get? We can invistigate this in the bivariate exploration. 

> 8- Most loans are taken by individuals that verified thier income. This makes sense, the unverifiable borrowers are only 95! 

> 9- The loan amounts range from few hundreds to 25,000 USD with clear spikes at loan amounts of USD 5000, 10000, 15000, 20000, 25000) 

> 10- The Montly Loan Payment histogram is right skewed and it has a long tail to the right, we will use a log scale on the x-axis to better see the plot. After transforming the x-axis to log scale the plot show the distribution of monthly loan payments that varry from 30 USD to more that 1000 USD / month and 2 spikes on the value of 200 USD and 500 USD. 

> 11- Heat map shows that most of the numerical features are not correlated. We only notice that high negative correlation between the Borrower Rate and the Prosper Score. The second correlation is between the Loan Original Amound and the montly loan payment and this one is expected.

> 12- The counts of loans are much higher if the borrower is a home owner, but this is not true for loans with values of 5000 USD or lower! 

> 13- The relationship between the Borrower rate and Monthly Loan Payment have a negative correlation.

> 14- Plotting the Loan Original Amount against the Term of payment which is either 12, 36, or 60 months shows thatthe mean value of the loan is increasing with the increase of the term of payment. 

> 15- The count of borrowers that have a rate between 0.15 and 0.35 are higher and it decreases as the loan amount increase. 




## Key Insights for Presentation

> 1- The point plot that shows the Loan Original amount in comparision to the income range for the borrower and we added a hue for the Term of payment (no. of months to payback the loan). It is clear that the loan amount increase as the income range increase and also as the term of payment increase. It is also noticed that borrowers who are not employed or their employment status is not displayed are only eligible for the 36 months term payment.

> 2- The Employment Status against the Loan Original Amount and we added a hue as the loan status. We notice from the graph that most of the 'past due (61 -120) days' loans lie in the 'Self employed & part timers' with a very wide confidence interval. In all other employment statuses, it seems that the current loans have higher values than completed ones. 

> 3- By plotting a box plot we see the mean values for loan amounts aginst the income range of the borrower and we added also a third variable if the borrower is a homeowner or not. It seems that the mean avarage loan amount is higher in case of homeowneres in all income ranges. 






