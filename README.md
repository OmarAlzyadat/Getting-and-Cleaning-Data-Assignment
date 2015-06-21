##Getting and Cleaning Data

This is a repository for any and all code written for the Getting and Cleaning Data Coursera course 

* Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into your working directory 
* Put run_analysis.R into your working directory
* In RStudio you can run the code included in the file named run_analysis.R by using source("run_analysis.R")
* The output of the above is also included in this repo under the name "data_set_with_the_averages.txt" you can view the data by using the following command: data <- read.table("data_set_with_the_averages.txt")
* It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. 
Note that the provided R script has no assumptions on numbers of records, only on locations of files.
