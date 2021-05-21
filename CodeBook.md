The source Data:  https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip  
A full description of the data is available at the site where the data was obtained: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Variables:
x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.

About R script:
File with R code "run_analysis.R" performs the 5 following steps (in accordance assigned task of course work):

Reading in the files and merging the training and the test sets to create one data set.
Reading files
Reading trainings tables
Reading testing tables
Reading feature vector
Reading activity labels
Assigning variable names
 Merging all data in one set
 
Extracting only the measurements on the mean and standard deviation for each measurement
Reading variable names
Create vector for defining ID, mean and standard deviation
Making nessesary subset from merged data set
Using descriptive activity names to name the activities in the data set
Appropriately labeling the data set with descriptive variable names
Creating a second, independent tidy data set with the average of each variable for each activity and each subject
5.1 Making second tidy data set
5.2 Writing second tidy data set in txt file
The code assumes all the data is present in the same folder, un-compressed and without names altered.
