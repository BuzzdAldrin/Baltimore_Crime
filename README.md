# Baltimore Crime Analysis Using Open Source Intelligence #

![Baltimore Police Helicopter](https://upload.wikimedia.org/wikipedia/commons/d/df/Baltimore_Police_helo_MD1.jpg)
https://upload.wikimedia.org/wikipedia/commons/d/df/Baltimore_Police_helo_MD1.jpg

#### *"For his eyes are upon the ways of man, and he seeth all his goings."* - Job 34:21-22 KJV ####

This R project statistically analyzes self-reported data from the Baltimore Police Department from January 2012 to November 2017. The data was obtained through the BPD [online portal](https://data.baltimorecity.gov/Public-Safety/BPD-Part-1-Victim-Based-Crime-Data/wsfq-mvij) as part of their [consent decree](https://consentdecree.baltimorecity.gov/).
At its core, this is a personal attempt at civic understanding. Why are things the way they are? How can we think about an emotional issue intelligently and without fear? It is difficult to have productive conversations about crime.

#### Motivation ####
This project's goal is to better understand both crime and law enforcement. In that regard it was humbling. The largest problem I had was not technical but probably "epistemological". There is so much nuance to the data. Trying to reduce it down to generalizable categories presents a legibility problem. Is a bus depot classified as transportation, municipal, or industrial? It sounds municipal but does it make sense for a crime happening at a bus depot overnight and one in a courthouse in daylight to be classified as municipal? It's splitting hairs and agonizing. It made me think of the book [Seeing Like a State](https://en.wikipedia.org/wiki/Seeing_Like_a_State) and it's ideas of ["high modernism"](https://www.newyorker.com/magazine/2017/09/18/the-case-against-civilization). High modernism is ["unfaltering confidence in science and technology as means to reorder the social and natural world"](https://en.wikipedia.org/wiki/High_modernism). It's a mantra that Silicon Valley and the Soviet Union both embody. It's a common idea today to solve problems with large technical solutions. Like when Mark Zuckerberg testified in Congress and [proposed a new software system](http://calnewport.com/blog/2018/04/11/the-disturbing-high-modernism-of-silicon-valley/) to stop Facebook's already running software from being used to manipulate voters. We simply cannot solve all problems yet by writing more complicated software. [(a great discussion about it on hackernews)](https://news.ycombinator.com/item?id=16819675). So this is a response to those who propose greater software solutions to solve great societal problems. It's bold and visionary thinking, but it's reductive and dangerous too. Take this as a testament to the difficulty it. Science, statistics, and engineering sometimes need to dive into the nuance.

There are too many ways of thinking about law enforcement. It can be analyzed through the lenses of communal, societal, or familial structure. An aproachable angle for a data scientist is to examine crime as an intelligence problem. What can be learned? And what actions can be done from that knowledge?

Onto the data. I'll break it down using [Donald Rumsfeld's partition of knowledge](https://www.youtube.com/watch?v=GiPe1OiKQuk)

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
