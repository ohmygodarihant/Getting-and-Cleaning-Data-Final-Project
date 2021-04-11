# How I modified the original dataset

I Merged the training and the test sets to create one data set.

Then I extracted the means and std. deviations for each dataset.

Then, I named each dataset.

I also appropriately named variables.

Lastly, I created a new tidy dataset with all the averages and new variables.

# Identifiers used

subject - ID of participant

activity - ID of activity type

# Variables left

(These all contain averages and std. deviations of the given data)

tBodyAcc-XYZ,
tGravityAcc-XYZ,
tBodyAccJerk-XYZ,
tBodyGyro-XYZ,
tBodyGyroJerk-XYZ,
tBodyAccMag,
tGravityAccMag,
tBodyAccJerkMag,
tBodyGyroMag,
tBodyGyroJerkMag,
fBodyAcc-XYZ,
fBodyAccJerk-XYZ,
fBodyGyro-XYZ,
fBodyAccMag,
fBodyAccJerkMag,
fBodyGyroMag,
fBodyGyroJerkMag

# For the Codebook

I added a new feature activitylabel - factor variable for : WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING.

The Tidy dataset was built as a mean values of features grouped by activitylabel and subject 
