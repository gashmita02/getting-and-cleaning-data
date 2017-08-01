# Getting and Cleaning Data - Course Project (Week 4)

This is the course project for the Getting and Cleaning Data Coursera course in Week 4.
The R script and `run_analysis.R`does the below mentioned tasks: 

1. Download the dataset if it does not already exist in the working directory. It can dowload from the provided URL.
2. Load the activity and feature info
3. Loads both the training and test datasets, keeping only those columns which
   reflect a mean or standard deviation using gsub function.
4. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset using cbind function.
5. Merges the two datasets using rbind function
6. Converts the `activity` and `subject` columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.
8. End result is shown in the file `tidy.txt`.
