# GettingAndCleaningData

The run_analysis.R script reads and labels movement data unzipped from the "Human Activity Recognition Using Smartphones" dataset unziped in the working directory

Subject and activity ids are bound to the test and trial datasets which are then bound together. 

A subset is made of the columns containing "mean" and "std" using grep.

A merge with the activity table labels the activity ids. 

The subsetted dataframe is aggregated by subject_id and activity_id applying the mean function to all variables to provide the tidy.txt dataset. 
