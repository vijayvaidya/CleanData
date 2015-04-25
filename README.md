# Cleaning Data Course Project 

Steps to run the run_analysis.R script
--------------------------------------
1. Set the dir where script resides as you working dir.
2. Download the data file required to complete assignment in working dir 
3. Create a new dir 'projectData' under the working dir
3. unzip the data for this project. 
4. Open run_analysis.R and source it in R studio

The script does following:
--------------------------
1. Reads the activity labels
2. Loads the feature
3. Select only mean and standard deviation 
4. Loads training and test data in two different frames
5, Merge both data frames into single one 
6. Claean Column names
7. Aggregate the combined data
6. Write the output to run_analysis.txt

