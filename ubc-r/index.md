---
layout: lesson
root: ../
title: Session content
---

Links *should I tiny URL these  ?*

  * Main landing page for boot camp: [http://jennybc.github.io/2014-05-12-ubc/](http://jennybc.github.io/2014-05-12-ubc/)
  * This page: [http://jennybc.github.io/2014-05-12-ubc/ubc-r/](http://jennybc.github.io/2014-05-12-ubc/ubc-r/) 
  * GitHub repository that makes our boot camp website and holds all official SWC lesson material: [https://github.com/jennybc/2014-05-12-ubc](https://github.com/jennybc/2014-05-12-ubc)
  * GitHub repository the instructors will develop during the boot camp: 
[https://github.com/jennybc/bioinformatics.ca-swc-r](https://github.com/jennybc/bioinformatics.ca-swc-r)
  * The GapMinder data excerpt: [http://tiny.cc/gapminder](http://tiny.cc/gapminder)
  * Our __public__ digital whiteboard: [https://etherpad.mozilla.org/ubc-r](https://etherpad.mozilla.org/ubc-r)

We will write R code together "live" in the sessions, but below I link to written content on some topics, for your future reference.

Session 1.1: Basics of the R working environment and language

  - Slides: [slides/session01_bootcamp-deep-thoughts.pdf](slides/session01_bootcamp-deep-thoughts.pdf)
  - [R basics, workspace and working directory, RStudio projects](http://www.stat.ubc.ca/~jenny/STAT545A/block01_basicsWorkspaceWorkingDirProject.html) -- [source](https://github.com/jennybc/STAT545A/blob/master/block01_basicsWorkspaceWorkingDirProject.rmd)
  - What does it mean to "write data for computers"?
    - Nine simple ways to make it easier to (re)use your data by Ethan P White, Elita Baldridge, Zachary T. Brym, Kenneth J. Locey, Daniel J. McGlinn, Sarah R. Supp. Ideas in Ecology and Evolution 6(2): 1–10, 2013. doi:10.4033/iee.2013.6b.6.f <http://library.queensu.ca/ojs/index.php/IEE/article/view/4608>. Section 4 "Use Standard Data Formats" is especially good reading.
    - Tidy data by Hadley Wickham. Submitted to The Journal of Statistical Software. Preprint available <http://vita.had.co.nz/papers/tidy-data.pdf>.  
  
Session 1.2: Care and feeding of R objects

  - Slides: [slides/session02_objects.pdf](slides/session02_objects.pdf)
  - [Basic care and feeding of data in R](http://www.stat.ubc.ca/~jenny/STAT545A/block02_careFeedingData.html) -- [source](https://github.com/jennybc/STAT545A/blob/master/block02_careFeedingData.rmd)
  - [R objects (beyond data.frames) and indexing](http://www.stat.ubc.ca/~jenny/STAT545A/block03_basicObjects.html) -- [source](https://github.com/jennybc/STAT545A/blob/master/block03_basicObjects.rmd)

Session 1.3: Version control, introduction

  - Slides: [Intro to practical version control for scientists](http://htmlpreview.github.io/?https://github.com/BernhardKonrad/2014-02-22-SFU/blob/gh-pages/BK-slides/git-intro.slides.html)
  - [Using Git with RStudio](session03_git.html)

Session 1.4: Making figures using `ggplot2`

  - Slides: [slides/session04_ggplot2.pdf](slides/session04_ggplot2.pdf)
  - [http://docs.ggplot2.org/](http://docs.ggplot2.org/current/)
  - [Overview of the R graphics landscape](http://www.stat.ubc.ca/~jenny/STAT545A/block90_baseLatticeGgplot2.html)
  - [Taking control of qualitative colors in `ggplot2`](http://www.stat.ubc.ca/~jenny/STAT545A/block17_colorsGgplot2Qualitative.html)
  - [Head-to-head comparisons of `ggplot2` and `lattice`](http://www.stat.ubc.ca/~jenny/STAT545A/block18_gapminderGgplot2VsLattice.html)
  - [Data Visualization with R & `ggplot2`](http://inundata.org/2013/04/10/a-quick-introduction-to-ggplot2/) by Karthik Ram (first few slides make a good introduction)

Session 2.1: Writing functions

  - [Writing functions](session05_Rfunctions.html)

Session 2.2: Data aggregation, including plyr

  - Slides: [slides/session07_dataAggregation.pdf](slides/session07_dataAggregation.pdf)
  - [`plyr` webpage](http://plyr.had.co.nz)
  - [Data aggregation](http://www.stat.ubc.ca/~jenny/STAT545A/block04_dataAggregation.html) -- [source](https://github.com/jennybc/STAT545A/blob/master/block04_dataAggregation.rmd)
  - [Data aggregation section](http://www.ugrad.stat.ubc.ca/~stat540/seminars/seminar04_compileNotebook-dataAggregation-twoGroupComparison.html#what-is-data-aggregation) of a tutorial from [STAT 540](http://www.ugrad.stat.ubc.ca/~stat540/)
  - A [Gist](https://gist.github.com/jennybc/697d3ede1a09682c2fb7#file-much_country-r) with R code that uses `plyr` to generate two files per country
  
Session 2.3: The shell, focus on file inspection and manipulation

Session 2.4: Version control, cont'd

  - [Getting Started with GitHub](session2.4_github.html)
  - What we drew on whiteboard: [slides/session07_git-github-rstudio.pdf](slides/session07_git-github-rstudio.pdf)

Session 2.5: Creating workflows and automated pipelines

  - Slides: [slides/session08_pipeline.pdf](slides/session08_pipeline.pdf)
  - [Getting data out of R](http://www.stat.ubc.ca/~jenny/STAT545A/block05_getNumbersOut.html) -- [source](https://github.com/jennybc/STAT545A/blob/master/block05_getNumbersOut.rmd)
  - [Writing figures to file](http://www.stat.ubc.ca/~jenny/STAT545A/topic12_writeFigureToFile.html) -- [source](https://github.com/jennybc/STAT545A/blob/master/topic12_writeFigureToFile.rmd)
  - [An introduction to `Make`](http://kbroman.github.io/minimal_make/) by Karl Broman, aimed at stats / data science types
