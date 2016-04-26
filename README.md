# Get-Clean-Assignment
# Getting and Cleaning Data - Method Summary

The GCFinal.R script does the following:

1	 Downloads and reads all relevant tables into the working directory  
2	 Combines the test and train data observations  
3	 Combines the activity codes and subject data for test and train datasets  
4	 Selects the mean and std columns, adds column label, and cleans up the labels  
5	 Combines all of the datasets  
6	 Aggregates and orders the data on activity (label) and subject (factors)  
7	 Computes the mean for each numeric column  
8	 Writes the group means to a new file, called tidy.txt
