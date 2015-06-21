# Getting and Cleaning Data Course Project
Parmod Kumar  
18 June 2015  

## Overview
This is the README file for the Getting and Cleaning Data Course Project. This README file explains how all of the scripts work and how they are connected. In this project, we need to collect, work with, and clean a data set. Finally, we need to prepare tidy data that can be used for later analysis.

Here we are submitting:

1. A tidy data set as described below.
2. A link to a Github repository with the script for performing the analysis.
3. A code book that describes the variables, the data, and any transformations or work that is performed to clean up the data called CodeBook.md.

## Dataset
The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained, see [The UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).

The data for this project can be found [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip).

## R script
Here, we have created a R script called run_analysis.R, which does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

### Setting the working directory
Please check the working directory and set as appropriate to access the dataset on your system.

## CodeBook.MD
Please refer to a code book (CodeBook.md) that describes the variables, the data, and any transformations or work that need to be performed to clean up the data.

