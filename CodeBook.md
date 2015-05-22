##Step 1. Merges the training and the test sets to create one data set.
x_train, y_train, x_test, y_test, subject_train and subject_test: the data from the downloaded files.

x_data, y_data and subject_data: merge the previous datasets to further analysis. 


##Step 2. Extracts only the measurements on the mean and standard deviation for each measurement. 

##Step 3. Uses descriptive activity names to name the activities in the data set.

library plyr is used. 

features: the correct names for the x_data dataset,stored in msfeatures (grep function is used), 
a numeric vector used to extract the desired data.

activities: the correct names for the y_data dataset (similar to the above approach). 

##Step 4. Appropriately labels the data set with descriptive variable names. 
all_data: merges x_data, y_data and subject_data. 

##Step 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
averages_data:tidy data with average, stored in a .txt file. 
