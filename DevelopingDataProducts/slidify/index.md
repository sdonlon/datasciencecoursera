---
title       : Developing Data Products
subtitle    : Course Project INSERT NAME
author      : Matt Dancho
job         : Cousera Data Science Specialization
framework   : revealjs        # {io2012, html5slides, shower, dzslides, ...}
revealjs:
  theme: default
  transition: convex
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : solarized_dark      # 
widgets     : [bootstrap]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2

This is slide 2


```r
library(ggplot2)
ggplot(data=mtcars, aes(x=hp, y=mpg, col=factor(cyl))) + geom_point()
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png)
