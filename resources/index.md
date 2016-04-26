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

<a name = 'sas'></a>

# SAS
I\'m still figuring SAS out\... I still prefer R\'s and Python\'s interactive programming options, object handling, and overall syntax. One resource that I found incredibly time-saving was [the iterlist macro](http://www.wuss.org/proceedings08/08WUSS%20Proceedings/papers/cod/cod06.pdf), since so much of my data preparation work involved applying the same transformations, yearly, to a list of variables. Having a macro to run another macro over a list of variables saved me lots of time.
