# Gradebook  
In this assignment you will be using 2D arrays to store grades that are read in from a data file.  
You will create two types of gradebook.
* A StandardGradebook that computes averages using all available grades.  
* A DropLowestGradebook that computes averages after dropping the lowest grade.  

# Data file  
The data file will formatted as shown in sample_data.txt.  
The first line will contain 2 integers that represent the number of students and the number of grades.  
The following lines contain a first name, last name, and the grades.  

# StandardGradebook  
## Constructor
The constructor will take a String that gives the path for the data file.  
The constructor should initialize arrays for the names of the students and their grades.  
The grades *must* be stored in a 2D array.

## toString()  
This method will print the entire gradebook.  To save screen space, only print the initials of the students.  

## studentAverage(int index)
This should calculate the average for the student at the given index (zero indexed).  
If the given index is out of bounds, return -1.  
For the sample data, studentAverage(0) would return 58.5

## assignmentAverage(int index)  
This should calculate the average for the assignment at the given index (zero indexed).  
If the given index is out of bounds, return -1.  
For the sample data, assignmentAverage(1) would return 94.5

## classAverage()  
This will calculate the average for the entire class.  It should work using the studentAverage method.  

# DropLowestGradebook
This should have the same methods as StandardGradebook, but calculate studentAverage differently.  
In this calculation, for the sample data, studentAverage(0) would return 58.5
If there is only one grade in the gradebook, it should NOT drop that grade.  

# Grading  
## Formatting (1 pt)  
Code should follow appropriate formatting for whitespace and tabs.  

## Commits (5 pts)  
At least 3 per day.  

## Structure (2 pts)
Minimal repetition of code.  

## Code
* constructors (3 pts)
* toString (2 pts)
* studentAverage (3 pts)
* assignmentAverage (2 pts)
* classAverage (2 pts)

