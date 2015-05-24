# Project Code Book

The data Description & Source.

* Description : http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

* Source : https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

## run_analysis.R does the following

### 1st script merges the training and test sets to create one data set.

* train/X_train.txt and test/X_train.txt which will give 10299 obs. of 561 variables

* train/subject_train.txt and test/subject_test.txt will give 10299 obs. of 1 variables

* train/y_train.txt and test/y_test.txt will give 10299 obs. of 1 variables

### 2nd script measures the mean and standard deviation for each measurement  will give 561 obs.

### 3rd script will give descriptive activity names to name the activities in the data set.

* walking

* walkingupstairs

* walkingdownstairs

* sitting

* standing

* laying

### 4th script will appropriately labels the data set with descriptive variable names in clean_data.txt 10299 obs. first 2 column is subject id and activity and others are meausurement

### 5th script will independent tidy data set with the average of each variable for each activity and each subject in dataset_average.txt with 180 obs with 30 subjects and 6 activities.


