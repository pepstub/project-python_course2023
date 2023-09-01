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

The concept of this project is moving all the Matlab and part of the R portions of my workflow to python. 

---

To demonstrate this, I considered an example experiment of the kind I would normally program, a variation on the additional singleton paradigm (Theeuwes, 1992).

To check out the material, download the two folders in this repository.
- the "scripts" folder contains two .ipynb files:
  - compiler_pycourse_project.ipynb compiles a condition file for the experiment with the required variables.
    After running it you should end up with a file named "Conditions.xlsx" in a folder of choice.
    It would be then loaded with the "builder" GUI of psychopy - required for online experiments, which I run.
    This accounts for the Matlab part of the workflow.
  - data_aggr_analysis_pre.ipynb is a data wrangling and aggregation script, to prepare data and perform some preliminary analyses.
    It accounts for part of the R portion of the workflow.
    To try it, I added an example csv with data I generated by performing the experiment myself - found in the "example_data_folder" 
    
