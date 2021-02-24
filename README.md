# Prosper loans dataset Investigation 
## Investigation Overview In this investigation I wanted to figure out two things: 
•	The factors which can be used to predict default on credit.
•	What factors influence Prosper rating.
## Dataset Overview 
This data set contains 113,937 loans with 81 variables on each loan, for the purpose of this investigation I've taken the following variables: Term, LoanStatus, BorrowerRate, ProsperRating (Alpha), ListingCategory (numeric), EmploymentStatus, DelinquenciesLast7Years, StatedMonthlyIncome, TotalProsperLoans, LoanOriginalAmount, LoanOriginationDate, Recommendations, Investors. After adjusting and wrangling dataset contained 26005 data points.

 ## Wrangling There were three major issues with data: 
1.	Need to remove pre 2009 data points entirely
2.	Stated monthly income had an unusually high number of outliers. You will need to drop all the data above three standard deviations from the mean.
After wrangling there are 26005 loans in data set. 

##Finding:
•	ProsperRating is an ordinal categorical variable with the following values from higher to lower ('AA', 'A', 'B', 'C', 'D', 'E', 'HR'), ratings have almost normal distribution in data set centered at 'C' the highest 'AA' and the lowest 'HR' ratings have the least occurrences.
•	Individuals with employment status 'employed' are more likely to have the maximum credit and completed one. while, others not. as noticed part time do not have any deafult loan and retired are the minimum
•	AAA prosper rating has the maximum borrowed amount in all three loan staus. Then comes HR as the lowest one
•	Loan category zero proved to be riskier than others. It needs more deep overview
•	Individuals with high rating tend to have higher monthly income.
