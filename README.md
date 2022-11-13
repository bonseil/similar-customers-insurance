# similar-customers-insurance

## Project Description

Insurance company wants to find customers similar to a given customer for marketing reasons. 
We need to use a Linear Regression model to find those customers, while obfuscating the data to ensure privacy.

## Steps in analysis

 - Opening the data files and studing the general information
 - Preparing the data 
 - Finding similar customers in raw and scaled data with different distances
 - Building a kNN classifier to identify customers belonging to a class
 - Linear Regression
 - Obfuscating the Data
 - Proving that the method chosen for obfuscating the data does not alter the results
 
## Data description
#### Features:
'Gender': '', 'Age': 'age', 'Salary': 'income', 'Family members': 'family_members', 'Insurance benefits': 'insurance_benefits
 - gender - insured person's gender
 - age - his or her age
 - income - the salary
 - family_members - the number of members in the family 
#### Target:
 - insurance_benefits - number of insurance benefits received by an insured person over the last five years.
