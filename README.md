# project-python_course2023
Final project for the Cimec python course 2023.

# Making my workflow python-centric.

In this first year of PhD my main activity has been coding psychophisics experiments with Psychopy. My topic of research is visuospatial attention and perception. 
An important element for the functioning of psychopy experiments are condition files. They are csv files in which rows correspond to trials, and columns to variables that may change across trials, for example the shape of an element, or its color, or duration. 
After the experiment is done, you also get results in the form csv files. 
I had learnt to generate and compile condition files in Matlab. Instead for preparing and analysing data my only previous experience was in R. 
So my workflow for the most part looked something like this: 
##### Psychopy > Matlab > Psychopy > R 
...not ideal. 

This project is concerned with moving all the Matlab and part of the R portions of my workflow to python. 
