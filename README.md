# (Dataset Exploration Title)
## by (your name here)


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. In this project we will be exploring a dataset known as the Prosper Loan Dataset. The Prosper Loan Dataset is a dataset that contains data of the loan platform known as 'Prosper'.

The present dataset are composed of 81 columns variables, and 113937 row records of loans data. Here we can find a table mostly composed of following data structure, such as float and int datatypes, in resume, we can find: 3 booleans, 11 int, 17 objects and 50 float.

Due to the exploration task, these datasets were further divided into a smaller dataframe called acquired_values containing just the variables of interest for our analysis. The acquired_values consists of 11 variables of which 7 are float, 1 is an int and 3 are of object type.


## Summary of Findings

In resume, in this dataset exploration of the Prosper Loan Data, the variable Loan Status was the main focus of the exploration. We explored what outcomes that affects the LoanStatus from the dataset.

We discovered that, the BorrowerRate had more impact on the status of the loans borrowed from Prosper Loans. It was discovered that the Loan status categories with a more positive outcome like the completed and FinalPaymentInProgress had lesser median value than those with negative outcome like Defaulted and Past Due that had higher median values. This was an indication that  higher borrower rate were more concentrated  in categories that indicates negative outcomes than those of positive outcomes. It was also possible to notice that, `BorrowerRate` and the `BorrowerAPR` are positively corrolated.


## Key Insights for Presentation

Below is a brief explanation of how the process for completing this project was carried out:

* First, We carried out some preliminary wrangling on the data. This involved loading the dataset and performing some cleaning operation on it like changing the ListingCategory from int to object datatype and replacing the numeric values to their corresponding categories.

* We then performed some univariate exploration on the variables of interest to see how the data is distributed.

* Next, we did some bivariate analysis on the variables of interest to observed how they relate with other variables

* Lastly, we completed the analysis by carrying out some multivariate exploration on the variable of interest, comparing it with other variables.