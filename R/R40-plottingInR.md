# Plotting in R


What may be confusing at first if you look at graphic examples is that R has several independent graphic engines. Think of it like having several drawing artists, every one with his/her own style. You can decide which one you want to use to represent your data. The two main one are 

* The standard graphic device, see many examples below
* ggplot2, see [here](http://www.cookbook-r.com/Graphs/)

There are more graphics engines though. Here is a [list of graphic packages that are available and how they fit together](http://mran.revolutionanalytics.com/taskview/info/?Graphics)

### Basic plotting example

The basic plotting command for the standard graphics output is plot() - this is a very simple example:


```r
x = 1:10
y = rnorm(10)
plot(x,y)
```

![](R40-plottingInR_files/figure-html/unnamed-chunk-1-1.png) 

### Links to learn more about R graphics

Here are some (hopefully) useful links on how to do more complicated graphics: 

* See Appendix 3 of the [Essential statistics](https://www.dropbox.com/s/8fmh10fdn6jd2xb/EssentialStatistics.pdf?dl=0) lecture notes

* [Graph example](https://github.com/biometry/APES/blob/master/Examples/Andrea/PlottingInR.md) page on APES

* [Wiki page with basic plotting examples](http://en.wikibooks.org/wiki/R_Programming/Graphics)

* [The Quick-R page](http://www.statmethods.net/graphs/creating.html) has more complete information about everytipe of plot

* Derek Ogle's book chapter is a [quick but clear introduction to plotting for Fisheries Analyses](https://5c3dc6c1-a-62cb3a1a-s-sites.googlegroups.com/site/fishrfiles/home/ifswr-drafts/Plotting_IntroFishAnalysisR.pdf?attachauth=ANoY7cqgeZWxKf36OxjHT4us56VkfzalvamJF5QAhzOEcUN_16c3YC7jO-B9X9qMju9DKW_XoMziYJyXU-pMYeyf593KPjkYSb5_q897f6jBbXykDcGhAz9jX1VD1sZQN_D5DTlp2BZXta3KNuCLAnrtReRZ3zQ6olNjTIKXVR8TwEebBQIyE2Tt90ihWEqU37bSNcQqtvyooFVE8BgXNdD5MRFDyGI411rtUUqf_whDVv7MFZkj9hOGXeCQ3LsMCamTZ0KEi6Ua&attredirects=0)

* Paul Maurell's book, ["R Graphics"](https://www.stat.auckland.ac.nz/~paul/RGraphics/rgraphics.html), is a resource that helps users to master the intricacies of R graphics

* How to change the [font](http://blog.revolutionanalytics.com/2012/09/how-to-use-your-favorite-fonts-in-r-charts.html) in R charts

* About changing the [background color in plots](https://stat.ethz.ch/pipermail/r-help/2003-May/033971.html)

* [How to plot mathematical annotation](http://vis.supstat.com/2013/04/mathematical-annotation-in-r/ and http://blog.revolutionanalytics.com/2013/04/math-symbols-in-r.html)

* [Some tips about how to improve R graphics](http://blog.revolutionanalytics.com/2009/01/10-tips-for-making-your-r-graphics-look-their-best.html)

* We can also find a R graphic's chapter in ["An Introduction to R"](http://cran.r-project.org/doc/manuals/r-release/R-intro.html#Graphics)

* For "production figures" (i.e. those submitted for publication), see [**Nature's Point of View series**](http://blogs.nature.com/methagora/2013/07/data-visualization-points-of-view.html)
 on scientific graphics (including colour coding, symbols and lines, all from top-notch designers!).
 
* In book form, check out Jean-luc Doumonts [Trees, Maps and Theorems](http://www.treesmapsandtheorems.com/), or look at some sample pages: [pdf](http://www.treesmapsandtheorems.com/pdfs/TM&Th-samplepages.pdf)

* [R Graph Catalog](http://shiny.stat.ubc.ca/r-graph-catalog/)
* [ Beyond Bar and Line Graphs: Time for a New Data Presentation Paradigm](http://www.plosbiology.org/article/comments/info:doi/10.1371/journal.pbio.1002128)

