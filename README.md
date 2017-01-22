#  Coursera - Getting and Cleaning Data Course Project
This is the course project for the Getting and Cleaning Data Coursera course.


## Introduction
The purpose of this project is to demonstrate ability to collect, work with, and clean a data set.
Deliverable, R script called `run_analysis.R` that does the following. 

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


## How to run R script
1. Download the dataset(UCI HAR Dataset) if it does not already exist in the working directory.
2. Donwload the R script `run_analysis.R` in the working directory
3. Type the command `source("run_analysis.R")` to run the R script on your R Sudio or R console
4. After few seconds `tidy.txt` will be made in the working directory


## Dependencies
The script run_analysis.R depends on the libraries `plyr`. If you have not installed it, please install it first.
```` R
install.packages("plyr")
````
