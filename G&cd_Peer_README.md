Getting and Cleaning Data - Peer Assessment
This repository contains the R script run_analysis.R to tidy Human Activity Recognition Using Smartphones Data Set. At the beginning script downloads the data set saving it as har.zip and unzips it into 'UCI HAR Dataset' directory while har.zip won't be downloaded if it exists already. After the loading and transforming data set script writes three tidy data sets:

The aggregate of test and train data sets, har-aggregate.txt.
The data frame with measurements of means and standard deviations, har-only-mean-std.txt.
The independent tidy data set, har-independent.txt.
Running the script in a command line:

$ Rscript run_analysis.R

or for Linux, MacOS:

$ ./run_analysis.R

Executing the script from the R console:

> source("run_analysis.R")

