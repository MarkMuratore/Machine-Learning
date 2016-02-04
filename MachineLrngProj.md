
# Predicting How Well Excercise was Performed
  -----------------------------------------

## Introduction
   ------------

This human activity recognition research has traditionally focused on discriminating between different activities, i.e. to predict "which" activity was performed at a specific point in time. The approach we propose for the Weight Lifting Exercises dataset is to investigate "how (well)" an activity was performed by the wearer. The "how (well)" investigation has only received little attention so far, even though it potentially provides useful information for a large variety of applications,such as sports training.

Six young health participants were asked to perform one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five different fashions: exactly according to the specification (Class A), throwing the elbows to the front (Class B), lifting the dumbbell only halfway (Class C), lowering the dumbbell only halfway (Class D) and throwing the hips to the front (Class E).

Read more: (http://groupware.les.inf.puc-rio.br/har).

Read more: http://groupware.les.inf.puc-rio.br/har#ixzz3zDIl6uwU  

## Data
   ----
   
The data for this project is from the UCI Human Activity Recognition (HAR) Smartphone data set. 30 subjects performed six activities (WALKING, WALKING UPSTAIRS, WALKING DOWNSTAIRS, SITTING, STANDING, LAYING) while wearing a smartphone. Movement data was captured from the accelerometer in the phone and recorded for analysis.

The data was partitioned into two data sets, training (70% of the volunteers), and test (30% of the volunteers). The data consisted of linear acceleration and angular velocity for subject x, y, and z axes.

The resultant data sets include:

* 'features_info.txt': Shows information about the variables used on the feature vector.
* 'features.txt': List of all features.
* 'activity_labels.txt': Links the class labels with their activity name.
* 'train/X_train.txt': Training set.
* 'train/y_train.txt': Training labels.
* 'test/X_test.txt': Test set.
* 'test/y_test.txt': Test labels.
* 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30.

## run_analysis.R script
   ---------------------
   
The run_analysis.R script performs the following five functions:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Code Book
   ---------
    
The code book describes the variables used to make the tidy.txt data set.





