# titanic
This is a Data Wrangling Exercise for Titanic Data set. This is a data set that records various attributes of passengers on the Titanic, including who survived and who didn’t.
Using R, we will be handling missing values in this data set, and creating a new data set. 

1: Port of embarkation

The embarked column has some missing values, which are known to correspond to passengers who actually embarked at Southampton. Find the missing values and replace them with S. (Caution: Sometimes a missing value might be read into R as a blank or empty string.)

2: Age

A lot of the values in the Age column are missing. While there are many ways to fill these missing values, using the mean or median of the rest of the values is quite common in such cases.

Calculate the mean of the Age column and use that value to populate the missing values

3: Lifeboat

We look at the distribution of passengers in different lifeboats, but as we know, many passengers did not make it to a boat. This means that there are a lot of missing values in the boat column. Fill these empty slots with a dummy value e.g. the string 'None' or 'NA'

4: Cabin

Notice that many passengers don’t have a cabin number associated with them. We created a new column has_cabin_number which has 1 if there is a cabin number, and 0 otherwise.
