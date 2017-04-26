One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

You should create one R script called run_analysis.R that does the following.

1.Merges the training and the test sets to create one data set.
2.Extracts only the measurements on the mean and standard deviation for each measurement.
3.Uses descriptive activity names to name the activities in the data set
4.Appropriately labels the data set with descriptive variable names.
5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

In my final Dataset, the variables are as following:
[1] "subject"                          "activity"                        
 [3] "timeBodyAccMean-X"                "timeBodyAccMean-Y"               
 [5] "timeBodyAccMean-Z"                "timeBodyAccStd-X"                
 [7] "timeBodyAccStd-Y"                 "timeBodyAccStd-Z"                
 [9] "timeGravityAccMean-X"             "timeGravityAccMean-Y"            
[11] "timeGravityAccMean-Z"             "timeGravityAccStd-X"             
[13] "timeGravityAccStd-Y"              "timeGravityAccStd-Z"             
[15] "timeBodyAccJerkMean-X"            "timeBodyAccJerkMean-Y"           
[17] "timeBodyAccJerkMean-Z"            "timeBodyAccJerkStd-X"            
[19] "timeBodyAccJerkStd-Y"             "timeBodyAccJerkStd-Z"            
[21] "timeBodyGyroMean-X"               "timeBodyGyroMean-Y"              
[23] "timeBodyGyroMean-Z"               "timeBodyGyroStd-X"               
[25] "timeBodyGyroStd-Y"                "timeBodyGyroStd-Z"               
[27] "timeBodyGyroJerkMean-X"           "timeBodyGyroJerkMean-Y"          
[29] "timeBodyGyroJerkMean-Z"           "timeBodyGyroJerkStd-X"           
[31] "timeBodyGyroJerkStd-Y"            "timeBodyGyroJerkStd-Z"           
[33] "timeBodyAccMagMean"               "timeBodyAccMagStd"               
[35] "timeGravityAccMagMean"            "timeGravityAccMagStd"            
[37] "timeBodyAccJerkMagMean"           "timeBodyAccJerkMagStd"           
[39] "timeBodyGyroMagMean"              "timeBodyGyroMagStd"              
[41] "timeBodyGyroJerkMagMean"          "timeBodyGyroJerkMagStd"          
[43] "frequenceBodyAccMean-X"           "frequenceBodyAccMean-Y"          
[45] "frequenceBodyAccMean-Z"           "frequenceBodyAccStd-X"           
[47] "frequenceBodyAccStd-Y"            "frequenceBodyAccStd-Z"           
[49] "frequenceBodyAccJerkMean-X"       "frequenceBodyAccJerkMean-Y"      
[51] "frequenceBodyAccJerkMean-Z"       "frequenceBodyAccJerkStd-X"       
[53] "frequenceBodyAccJerkStd-Y"        "frequenceBodyAccJerkStd-Z"       
[55] "frequenceBodyGyroMean-X"          "frequenceBodyGyroMean-Y"         
[57] "frequenceBodyGyroMean-Z"          "frequenceBodyGyroStd-X"          
[59] "frequenceBodyGyroStd-Y"           "frequenceBodyGyroStd-Z"          
[61] "frequenceBodyAccMagMean"          "frequenceBodyAccMagStd"          
[63] "frequenceBodyBodyAccJerkMagMean"  "frequenceBodyBodyAccJerkMagStd"  
[65] "frequenceBodyBodyGyroMagMean"     "frequenceBodyBodyGyroMagStd"     
[67] "frequenceBodyBodyGyroJerkMagMean" "frequenceBodyBodyGyroJerkMagStd" 


So after finishing this project, I got the R script of run_analysis and a MeanData.txt~

