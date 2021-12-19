Please follow these steps to get to the requiered file for this Project

# Dataset
"https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"

# About the data

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

# The Project

The code in file run_analysis.R runs the following processes in order to obtain the tidy data set required for this module as follows: 

  ### 1. Merge the training and test datasets
    1.1 Read files
      1.1.1 Read training datasets
      1.1.2 Read test datasets
      1.1.3 Read feature vector
      1.1.4 Read activity labels
    1.2 Assign variable names
    1.3 Merge all datasets into one set
  ### 2. Extract mean and sd for each measurement
    2.1 Read column names
    2.2 Create vector for defining ID, mean, and sd
    2.3 Make nessesary subset
  ### 3. Use descriptive activity names
  ### 4. Label the data set with descriptive variable names
  ### 5. Create a second,  independent tidy data set with the avg of each variable for each activity and subject
    5.1 Make a second tidy data set
    5.2 Write second tidy data set into a txt file
 
 # Variables
 
  ### Variable Names
    features.txt
    SubjectID
    ActivityID
  
  ### Data 
    Train Data
      X_train.txt
      subject_train.txt
      y_train.txt
     Test Data
      X_test.txt
      subject_test.txt
      y_test.txt
     activity_labels.txt
