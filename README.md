# Coursera Getting and Cleaning Data - Course Project

Following is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, performs the following tasks:

1. Unzips the downloaded UCI HAR dataset in the working directory, if the folder does not already exist
2. Loads the activity and feature info
3. Loads both the training and test datasets, keeping only those columns which
   reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset
5. Merges the two datasets
6. Converts the `activity` and `subject` columns into factors
7. Creates the final tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.

The end result is shown in the file `tidyData.txt`.
