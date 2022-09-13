# (Dataset Exploration Title)
## by (your name here)


## Dataset

> This data set contains 113,937 loans from 2005 to 2014 with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.


## Summary of Findings

> Most of the loans are of status `current`, forming almost half of the entire dataset. To focus on other loan statuses, current loans are excluded. Alomost a half of the remaining loans are also completed. I noticed that there are about 4 variables that appears for only loans after July 2009. After excluding current loans and further splitting the data into periods before and after July 2009, it can me observed that some loan status are unique to only the period July 2009 onwards and is probably due to when the listing was made.
Before July 2009 there no cancelled loans but quite a number have a `Past Due` status of a sort.  There are $5$ cancelled loans After July 2009 but no loans with a `Past Due` status. Could the additional features in the dataset present for only the period after July 2009 have influenced this observation? Both periods have large number of loans with status `Completed`, `Chargedoff` or `Defaulted`.

> However the 4 additional variable for the period after July 2009 do not seem to have any influence on the outcome of loan status in the that period.

## Key Insights for Presentation

>  $50,000$ plus of loans in the dataset have a current status and close to $40,000$ are completed. Plotting on a log scale, shows the value of other loan status with count below $10,000$. Since current loans are not in a final status we focus on loans of other statuses. Majority of the loans with `completed` status have borrowers with employment status of `employed` or `full-time`. This form more than half of the dataset. Most loans irrespective of amount and status have a term of $36$ months or $60$ months. Borrower rate appears to be with the range $0.2 -0.4$ percent irrespective of loan amount with few loans having a borrower rate greater than $0.4$ percent.

> There does not appear to be a strong relationship between final loan status and the any of the other variables