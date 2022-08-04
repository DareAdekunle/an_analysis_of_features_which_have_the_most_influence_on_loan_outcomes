# Part II - An analysis of trends across Loan Status
## by Oludare Adekunle


## Dataset

> Loan Data from Prosper: This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. See this data dictionary to understand the dataset's variables. Of the available features, in this project I chose to work with a subset of the data using the following features: Listing Creation Date, Term, Loan Status, Borrower Apr, Borrower Rate, Listing Category, Borrower State, Occupation, Employment Status, Employment Status Duration, Is Borrower Home Owner, Credit Score Range Lower, Credit Score Range Upper, Revolving Credit,  Balance, Bank Card Utilization, Available Bank Card Credit, Debt To Income Ratio, Income Range, Income Verifiable, Stated Monthly Income, Monthly Loan Payment, Recommendations, Investors, Loan Original, Amount. 

The aim of this project is to investigate how various factors inflence Loan outcomes listed in the loan status column.

## Summary of Findings

> From carrying our univariate, bivariate and multivariate analysis of the data, I found the following:

<ol>
    <li>From analysing the loan status, I found out that of the current observations in the data, 50% are currently under a type of loan, 33% completed the loan, while 17% belond to some state of defaulted, charged off or past due.</li>
    <li>3588 (3.15%) of the occupation data was missing</li>
    <li>Non specific occupation types (other and professional) represents the most occupation type to borrow loans.</li>
    <li>Borrowers annual exchange rate has more unique values than borrowers rate as it shows an all year round moving average.</li>
    <li>Both borrowers annual percentage rate and borrowers rate appear to have a normal distribution </li>
    <li>The difference between the credit score range - upper and lower, is the start values and end values, of which the upper range offsets the lower range by 19</li>
    <li>there is a appear to be outliers credit score range - upper and lower</li>
    <li>Observations with a lower credit score greater than 600 and an upper credit score less than 820, represent the bulk of our observations.</li>
    <li>There are 133 outliers in the credit score range. There are observations abnormally low credit scores who were offered loans.<br>Of these lots, approximately 60 have defaulted, 35 have been charged off while 38 have been completed.</li>
    <li>in almost all loan status category, I found that the reason for which our observation borrowed loans the most is for debt consolidation. <br>However, when we look at the defaulted categorywhere we expect to find similar trend of debt consolidation topping the list we find that, observations where there is no record of what the loan is used for tops the chart.</li>
    <li>Observations for which we have no record of what they were used for, also takes the lead in the loans that have been charged off.</li>
    <li>Observations in the completed loans category, are clustered more around the lower boundary of the borrower rate and have a median borrower rate of less than 0.2. <br>This trend is similar with Current loans category of loans</li>
    <li>observations in the defaulted, cancelled, past due categories of the loan status features are cluster more towards the upper boundaries of the borrower rate and generally have a median borrower rate of 
    greater than 0.2</li>
    <li>The credit score does not show any clear relationship between the </li>
    <li>Most current loans are borrowed by employed.</li>
    <li>Full time category show the best performance on loan completion but also the worst as it has the highest defaulted and charged off loans.</li>
    <li>The not-displayed and 0 category of the income range have an unusually high number of charged off or defaulted.</li>
    <li>Current loans have a higher median amount than any other category</li>
    <li> Average monthly income of those who completed their payments do not vary much against those who did not defaulted or had thier loans Charged off.</li?>
    <li> Generally, there is a less borrower rate for home-owners.</li?>
    <li> Distribution of our observation across the different status is thesame for both home-owner and non-home-owner except in the defaulted status where concentration of observations of home-owners that defaulted have high borrower rate, while reverese is the case for non-home-owners.</li?>
    <li> Regardess of home-owner status, low borrower rate tends plays a role in enabling completion of loan status.</li?>
    <li> From the plot we can see that the relationship is a little less negative for Home owners when compared with non home owners.</li?>
    <li> Across the different Loan status, we see that lower term loans have lower interest rates.</li?>
    <li> Accross all loan terms, completed loans frequencies are clustered around lower rates while frequencies for past due defaulted are clustered around higher interest rates.</li?>
</ol>



## Key Insights for Presentation

> The goal of my Exploration was to determine what factors influence the outcomes an offered loan in order To improve collections on loans offered. Thus, the key insights for my presentation are listed below:
<ol>
    <li>Current distribution of all offered loans across loan staus catogories</li>
    <li>The effect borrower rates have on loan status outcomes</li>
    <li>The effect the reason for which a loan is borrowed has on loan status outcomes</li?>
    <li>The effect the eployment status of an individual has on loan status outcomes</li>
    <li>the relationship between loan terms and borrower rate on loan status outcomes.</li>
</ol>