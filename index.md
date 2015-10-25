---
title       : Developing Data Products Course Project
subtitle    : Predict Cars Consumption App
author      : Anderson Roberto Santos dos Santos
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Developing Data Products Work

### Author: Anderson Roberto Santos dos Santos
  
In this project, we developed a shiny application that predicts the Miles Per Gallon consumption of a car based in some features of it. These set of features where selected based on how easy is for the user to collect them.

--- .class #id 

## The features

* Number of cylinders
* Gross horsepower
* Weight (lb)
* Number of forward gears
* The transmission type: Automatic or Manual

---  

## How the prediction model was created

* We used the mtcars dataset from the dataset package in R  
    * _The data was extracted from the 1974 Motor Trend US magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973–74 models)._   
* Use used the linear regression model in R  

---  

## The model coeffitients


```
##    (Intercept)            cyl             hp             wt           gear 
##     37.1873000     -0.8060183     -0.0233920     -2.6313041     -0.2411571 
## as.factor(am)1 
##      1.6657414
```


