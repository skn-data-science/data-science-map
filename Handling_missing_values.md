# Handling missing values
## Definition
Missing data is a dataset which rows is characterised by missing values in specific attributes
## Reasons behind missing data
1. Missing at Random (MAR) - propensity of data is not related to missing data, but is related to some of observed data. 
2. Missing Completely (MCAR) - missing value has nothing with its hypothetical value and with values of other variables, e.g, lost questionaires or destroyed samples
3. Missing not at random (MNAR) - missing value depends on the hypothetical value, e.g. disclosure of the fact of high earnings or is dependent on some other variable e.g. willingness to reveal about age may vary by gender
## How to handle data missing data?
### Removing:
- Litwise deletion - removing all data for an observation that has one or more missing values
- Pairwise deletion - using non-missing data from observations containing missing values for statistical purpose
- Deleting columns - dropping attributes if data is missing in specific and significant amount 
### Imputation:
- Statistical imputation - using statistical methods to estimate a specific value based on non-missing values in column and replacing all missing values with it
- KNN imputation - utilizzing the k-Nearest Neighbors method with the mean value
- Multiple imputation - creating m complete datasets using different imputation methods to achive reliable and final result
## Summary
- Choosing method for handling missing values in dataset mostly depends on analyzed problem and no solution is universal. 
- It is always better to try imputing missing data in the first step rather than to delete it
- Observations which lackness in values can be described as MCAR, are safe to remove
## More information and useful links
- [Types of missing data](https://www-users.york.ac.uk/~mb55/intro/typemiss4.htm#:~:text=When%20we%20say%20data%20are,CADET%2C%20sex%20might%20be%20MCAR. "Title")
- [Listwise vs. Pairwise deletion](https://www.ibm.com/support/pages/pairwise-vs-listwise-deletion-what-are-they-and-when-should-i-use-them#:~:text=Pairwise%20deletion%20occurs%20when%20the%20statistical%20procedure%20uses,case%20when%20analyzing%20other%20variables%20with%20non-missing%20values. "Title")
- [Handling missing data](https://towardsdatascience.com/how-to-handle-missing-data-8646b18db0d4 "Title")



