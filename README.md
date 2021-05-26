# PGA_Gettign-and-Cleaning-Data_Week4

This is the README file for the peer graded assignment of Getting and cleaning data. In order to complete this PGA, we need to download the raw data files and unzip it. We'll then have to process it to a clean and neat set of data.

## Description of Data

 The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone.
 
## R script analysis
1. Merges the training and the test sets to create one data set. Use command rbind to combine training and test set
2. Extracts only the measurements on the mean and standard deviation for each measurement. Use grep command to get column indexes for variable name contains "mean()" or "std()"
3. Uses descriptive activity names to name the activities in the data set Convert activity labels to characters and add a new column as factor
4. Appropriately labels the data set with descriptive variable names. Give the selected descriptive names to variable columns
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. Use pipeline command to create a new tidy dataset with command group_by and summarize_each in dplyr package
