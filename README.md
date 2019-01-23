# HARtidydata
## Getting and cleaning data project

This repository is a requirement for the Getting and Cleaning Data course project. 

Dataset
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Files:

CodeBook.md describes the variables, the data, and the cleaning process.

run_analysis.R performs the following: 
0. Prepares and downloads data.
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

FinalData.txt is the exported final data after going through all the sequences described above.
