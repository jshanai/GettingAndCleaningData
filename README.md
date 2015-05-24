# This code reads data from: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
# The zip file needs to be extracted into a folder where the .R code should exist
# Name of .R is run_analysis.R

# This R script does the following:

# 1. Merges the training and the test sets to create one data set.
# X holds X training and test data
# S holds Subject training and testdata
# Y holds Y training and testdata

# 2. Extracts only the measurements on the mean and standard deviation for each measurement.
# X holds the mean and standard deviation for each measurement

# 3. Uses descriptive activity names to name the activities in the data set.
# Y holds descriptive activity names to name the activities in the data set

# 4. Appropriately labels the data set with descriptive activity names.

# 5. Creates a 2nd, independent tidy data set with the average of each variable for each activity and each subject.
