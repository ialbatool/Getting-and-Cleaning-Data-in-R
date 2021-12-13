### The dataset was created by following the 5 steps

1. Merging the training and the test sets to create one data set.
2. Extracting only the measurements on the mean and standard deviation for each measurement. 
3. Using descriptive activity names to name the activities in the data set
4. Appropriately labeling the data set with descriptive activity names. 
5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject. 

### R script
R code "run_analysis.R" execute the above 5 steps

### Variables:   
- `x_train`, `y_train`, `x_test`, `y_test`, `subject_train`, `subject_test`: data from the downloaded files
- `x_data`, `y_data`, `subject_data` merge the previous datasets
- `features` is the corect name for the `x_data` dataset
