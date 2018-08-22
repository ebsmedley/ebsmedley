---
layout: post
title:  "Code Snippets"
date:   2018-08-22
excerpt: "Practice uploading .Rmd code"
tag:
- sample
- post
- code
comments: false
---


This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

    summary(cars)

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

Including Plots
---------------

You can also embed plots, for example:

{% capture images %}
    https://raw.githubusercontent.com/ebsmedley/ebsmedley.github.io/master/_posts/Code_Snippets_files/figure-markdown_strict/pressure-1.png
{% endcapture %}
{% include gallery images=images caption="" cols=1 %}


Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
