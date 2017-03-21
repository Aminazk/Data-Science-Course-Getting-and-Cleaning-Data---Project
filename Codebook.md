The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. 
The goal is to prepare tidy data that can be used for later analysis. 

The data for the project are available from this link:
        
        https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
        
 The R script, in a file called:"run_analysis.R", and performs the following:
        
1. Downloads the dataset if it does not already exist in the working directory.
2. Loads the activity and feature information.
3. Loads both the training and test datasets, keeping only those columns which 
reflect a mean or standard deviation.
4. Loads the activity and subject data for each dataset, and merges those columns 
with the dataset.
5. Merges the two datasets.
6. Converts the activity and subject columns into factors.
7. Creates a tidy dataset that consists of the average (mean) value of each variable for each 
subject and activity pair. The end result is shown in the file called: "tidy.txt."


About variables:

x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.

x_data, y_data and subject_data merge the previous datasets to further analysis.

features contains the correct names for the x_data dataset, which are applied to the column names.
