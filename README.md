# Getting and Cleaning Data Course Project
This is the course project for the Getting and Cleaning Data Coursera course. The R script, run_analysis.R, does the following:
1. Downloading and unzipping dataset
2. Merging the training and the test sets to create one data set
2.1 Reading files
2.2 Assigning column names
2.3 Merging all data in one set
3. Extracting only the measurements on the mean and standard deviation for each measurement
3.1 Reading column names
3.2 Create vector for defining ID, mean and standard deviation
3.3 Making nessesary subset from setAllInOne
4. Using descriptive activity names to name the activities in the data set
5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject
5.1 Making second tidy data set
5.2 Writing second tidy data set in txt file
