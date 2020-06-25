
	
# Project: Global Shark Attacks Analyis

## Overview
[The target of this project to answer to one problematics using the dataset : Sharks](https://www.kaggle.com/teajay/global-shark-attacks/version/1)
For this analysis I have taken the point of view of a research center like the Scharkschool which mission is to change the negative picture and the sterotypes the sharks are suffering from.
Here the questions I will to answer to using this dataset. :
	* Are shark attacks more frequent than ever? How much deadly they really are.


##Steps followed:
 ###Import of the file 
 
 ###Analysis of the file structure:
 	- name of columns
 	- number of rows/columns
	- number of empty/not empty cells per column
	- Type of data, syze of the dataset
	- check the frequency of each element for each column ==> define whether the column requires an important cleaning
	
 ### General claning:
 	- Clean column titles => to ease selection 
    - Delete empty rows and columns
    - Delete duplicated rows and columns
    - check whether it is worth keeping 3 columns case number
### Definition of a function to get the quickly the main information about the column before starting the cleaning

### Column cleaning
	The questions to be answerered are: "Are shark attacks more frequent than ever? How much deadly they really are"
	So we will need to use the column, Year, Fatal ((Y/N)) and Injuries to see whether all attacks lead to injuries.
	Before using the data of this column we clean the data in order to have the best possible picture.
	# Cleaning steps:
		Get a description of the colomn
		Correct the typo errors
		Fill in the missing values in order to keep the row or drop it if not relevant
		drop values which are not relevant for the analysis.
	# Graph the data to see the evolutions
		
