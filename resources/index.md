---
layout: default
title: Robert Gambrel - Helpful Resources
---
I learn a lot from online tutorials and StackExchange discussions, so I thought I should share a few I found particularly useful.

<a name = "git"></a>

# Git and GitHub
I first started using git after discovering that RStudio supported it as part of Projects. I [browsed](https://jennybc.github.io/2014-05-12-ubc/ubc-r/session03_git.html) a few [different resources](https://jonlefcheck.net/2013/11/04/a-basic-tutorial-to-version-control-using-git/) to get the hang of it, but [Christian Lemp\'s guide on handling branches](http://christianlemp.com/blog/2014/02/13/How-I-Manage-Data-Projects-with-RStudio-and-Git-Part-2.html) was what really helped me understand how useful version control could be for my own work.

<a name = 'r'></a>

# R
The [dplyr](https://github.com/hadley/dplyr) package for data manipulation has made my life so much easier. In fact, my first big git branch endeavor was used to re-write many of my scripts to take advantage of dplyr\'s syntax clarity and speed, especially for groupwise operations. The [official vignette](https://cran.rstudio.com/web/packages/dplyr/vignettes/introduction.html) stays updated with new functionality, and I followed [these examples](http://datascienceplus.com/data-manipulation-with-dplyr/) as well. More recently, I\'ve found [this guide on dplyr\'s ability to interact with databases](http://datascienceplus.com/working-with-databases-in-r/) to be particularly helpful, as I came across it just as we started a new project that needed a local database set up.

Hadley Wickham's book on [creating and publishing R packages](http://r-pkgs.had.co.nz/) guided me through creating two of my own packages: [medicare](https://github.com/robertgambrel/medicare) and [tabler](https://github.com/robertgambrel/tabler). In addition, his book on [advanced R programming](http://adv-r.had.co.nz/), especially his coverage of non-standard evaluation, really helped me utilize the functionality from his other packages when writing my own.

<a name = 'python'></a>

# Python
I learned the Python basics by working through all the [Learn Python the Hard Way](https://learnpythonthehardway.org/) lessons and completing the [Introduction to Computer Science and Programming using Python](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-11) course from MIT on edX. After those, I continued to learn by doing and now conduct machine learning, web scraping, and task automation using Python and its libraries.

<a name = 'sas'></a>

# SAS
I\'m gradually coming around to SAS\... I still prefer R\'s and Python\'s interactive programming options, object handling, and overall syntax. One resource that I found incredibly time-saving was [the iterlist macro](http://www.wuss.org/proceedings08/08WUSS%20Proceedings/papers/cod/cod06.pdf), since so much of my data preparation work involved applying the same transformations, yearly, to a list of variables. Having a macro to run another macro over a list of variables saved me lots of time.
