# Baltimore Open-Source Intelligence Crime Analysis

#### *"For his eyes are upon the ways of man, and he seeth all his goings."* - Job 34:21-22 KJV ####

This R project statistically analyzes self-reported data from the Baltimore Police Department released as part of their consent decree.
At its core, this is a personal attempt at civic understanding. Is there another way? 
There are too many ways of thinking about crime. It can be analyzed through the lenses of policing, drug policy, or familial structure. An aproachable angle for a data scientist is to examine crime as an intelligence problem. 

#### *"There are known knowns...* ####

Data covers January 2012 through November 2017. There are three datasets: arrests, calls, and victims. Arrests deals with police reports leading to arrests. Calls deals with police reports associated with a 911 call. Victims deals with police reports from victim based crimes. Data includes:

1. Police Code
2. Location: both an address and a latitude longitude pair
3. Description
4. Neighborhood
5. And more

Data will not be tracked in Git due to its size.
The data was obtained through the Baltimore Police Department's Website.
https://www.baltimorepolice.org/crime-stats/open-data

To run any of the code I have created to analyze the data, you have to create a Data folder of your git repo. Be sure not to commit that (the gitignore should handle csv files).
Be sure to either name the files the same way that I do or edit the import statements to reflect your new names.
Files are presented as both R Markdown (.rmd) and regular R (.r) for use in RStudio or command line.
