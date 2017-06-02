##OVERVIEW
This repository hosts the content required for the Getting and Cleaning Data Course; the run_analysis.R script, a tidy dataset and a codebook.

##DATA
The data set being used in this, can be found here: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

##FILES
CodeBook.md describes all the variables and summaries calculated, along with units, and any other relevant information.

run_analysis.R is a script which does the following; merges the training and the test sets to create one data sets, extracts only the measurements on the mean and standard deviation for each measurement, uses descriptive activity names to name the activities in the data set, appropriately labels the data set with descriptive variable names and creates an independent tidy data set with the average of each variable for each activity and each subject.

The output of the run_analysis script is the tidy_dataset.txt file