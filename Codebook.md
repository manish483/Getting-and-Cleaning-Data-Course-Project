## The original data was transformed by
1. Merging the training and the test sets to create one data set.
2. Extracting only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labeling the data set with descriptive activity names. 
5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject. 

## About R script
File with R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work)

## About variables:   
* 'testset', 'testlabels','testsubjects',`trainset','trainlabels' & 'trainsubjects' contain the data from the downloaded files.
* 'alltest','alltrain' are all test & train datasets which has been merged together as 'traintest' datasets for further analysis.
* `features` contains the renames of all the feature columns according to the feature data
