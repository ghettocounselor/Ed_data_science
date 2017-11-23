Example of Getting and Cleaning Data for Future Use

The purpose of this project is to collect, work with, and clean a data set, yielding tidy data that can be used for later analysis. The data represents data collected from the accelerometers from the Samsung Galaxy S smartphone.

A full description is available at the site where the data was obtained: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

In this project I created an R script called run_analysis.R that does the following:

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
The complete set of outputs including the run_analysis.R and tidyData.csv and CodeBook.md reside in the following GitHub repository https://github.com/edloessime/tidy_data_merging_week4
