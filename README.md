Description
------------
The tidy data set in results.txt contains the mean average of the mean and std deviation variables from the source sets X_train.txt and X_test.txt, analysed by subject and activity.  

Process
----------
The data was processed as follows :  
1. Each dataset was loaded and prepared as follows:  
    1.1. it was decorated with column names from features.txt.  
    1.2. the unwanted column names were removed  
    1.3. the column names were processed via some pattern matching to make them more descriptive.  
    1.4. each row was decorated with the activity and subject descriptions  
2. The training and the test observations were merged into a single dataset.  
3. Mean averages were calculated and analysed by Activity description and subject to create a the tidy data set.  

Implementation
----------------
The above is all accomplished in the run_analysis.R script.  

References
----------------
[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012  

