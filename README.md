## GETTING-AND-CLEANING-DATA-COURSE-PROJECT

The purpose of this project is to demonstrate the ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.

One of the most exciting areas in all of data science right now is wearable computing. Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone.

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

For the purposes of this project, the files in the Inertial Signals folders are not used.

The files that will be used to load data are listed as follows:

•test/subject_test.txt

•test/X_test.txt

•test/y_test.txt

•train/subject_train.txt

•train/X_train.txt

•train/y_train.txt


PROJECT ASSIGNMENT FOR THE COURSE - GETTING AND CLEANING DATA

R script called run_analysis.R in this repository does the following:

1.Merges the training and the test sets to create one data set.

2.Extracts only the measurements on the mean and standard deviation for each measurement. 

3.Uses descriptive activity names to name the activities in the data set

4.Appropriately labels the data set with descriptive variable names. 

5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The final output is generated as a text file - tidy.txt
