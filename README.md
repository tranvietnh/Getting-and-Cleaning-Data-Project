# R script

# About
  Information about the variables, data and transformations used in the assignment in Getting and Cleaning Data course.
## R script
1. Downloading and unzipping data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
2. Reading the activiy labels and features then extracting the information needed for the following steps.
3. Reading and extracting only the measurements on the mean and standard dviation of the training dataset
4. Reading the extracting only the measurements on the mean and standard dviation of test dataset
5. Mergeing training and test dataset into one dataset and adding labels then Exporting the combined dataset as tidyData.txt.
## Variables
1. x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
2. x_train, y_train, and subject_train are merged as train. x_test, y_test, and subject_test are merged into test.
3. train and test are combined into one dataset called combined
3. features contains the names for the dataset combined, which are applied to the column names.
