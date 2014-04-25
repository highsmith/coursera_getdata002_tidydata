coursera_getdata002_tidydata
============================

About
-----
The run_analysis.R file extracts data for the Coursera getdata002 Tidy Data class project.

The data is from the Human Activity Recognition Using Smartphones Data Set at UCI's Center for Machine Learning and Intelligent Systems.

data source: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

runanalysis.R
-------------
The script reads in 8 files:  
1.test data  
2.train data  
3.test subject identifier  
4.train subject identifier  
5.variable names  
6.observation index for test data  
7.observation index for train data  
8.obervation names  
  
A single tidy data structure is assembled, extracting only the measurements of "\*mean()" or "\*std()" and the descriptors subject and activity.

The mean of each measurement is aggregated along subject and activity.


