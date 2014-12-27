## Book: Handling Large R Projects (HLRP)

There are many publications on how to solve different data mining, data analysis and modeling tasks in R. Typically a task is a specific procedure to analyze a specific data, e.g. k-means clustering of iris data, and requires 10-100 lines of R code. Usually the tasks are grouped in projects, e.g. analyze iris data, that could include descriptive statistics, principal component analysis, MDS, clustering, classification, etc., that can require 500-3000 lines of R code.

But usually an R user has to work not with one task, but with a number of data mining projects in the same time, and each of the projects has many tasks. For example he/she might start project A, then switch to project B, then to project C, then after a few weeks or months return back to A and continue to work with it and so on. In each project R code can consists of many files and have thousands lines of code, which often creates problems in navigation through the code. Some tasks in a project could have long execution time that makes difficult to use usual literate programming methods (as sweave, knitr).
This situation is typical for all professional R users, but there is no literature how to treat this situation.

We describe how to minimize overhead of switching between number of large projects and deliver results in minimal time.

The project contains a collection of our code snippets, including over fifty R functions in about 1500 lines of code that we developed for this purpose, that considerably (2-3) times increases productivity.

### Table of Contents

* Preface
  
* Chapter 1. Workflow of R Projects	

* Chapter 2. Reporting, Reproducible Research and Literate Programming	
  2.1. External reports. Packages knitr, highlight, brew, R2HTML	
  2.2. Internal reports. Code2HTML() or rwj()	
  2.3. Releases. ReleaseOut()	

* Chapter 3. IDE: which to prefer?  
    3.1. RStudio	
    3.2. Eclipse + StatET	
    3.3. Other (vim, ess,..)	
  
* Chapter 4. Naming and style conventions
	
* Chapter 5. Structure of a project directory	
  5.1. Package ProjectTemplate	
  5.2. CreateProject()	
  
* Chapter 6. Helper functions to work with a number of large projects	
  6.1 Our helper functions	
  6.2. Creation demo_HLP project	
  6.3. Leaving (How to leave a project)	
  6.4. Coming back (How to come back and continue to work with a project)	
  6.5. Helper functions to work with R code	
  
* Chapter 7. R Work Journal    
  7.1. What is it	
  7.2. How to create it. rwj(), Code2HTML(); MakeRWJournals()	
  7.3. How to create album. Function createRWJalbum()	
  7.4. What is release and function ReleaseOut()
  
* Chapter 8. How to...	
  8.1. How to run different tasks in parallel. Working with multiple consoles	
  8.2. How to use your own packages and source files	
  8.3. How to combine R with other scripts: shell, hive, etc. in a project	
  8.4. How to work with R on remote server	
  8.5. How to work with source control systems	
  8.6. How to work on laptop with additional monitors	
  
* Chapter 9. Appendix. R code	
    9.1. Package HalaP -	http://github.com/alexzolot/HaLaP  
    9.2. Package RWorkJournal -  http://github.com/alexzolot/RWorkJournal   
    9.3. Example demo_RWJ.r file -  http://alexzolot.github.io/RWJ/demo_RWJ.r.htm   
    9.4. Example demo_HLP project	-  http://alexzolot.github.io/HLP/demo_HLP.r.htm  
  
* References	
* Index	


