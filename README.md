# Homework 09: Analyzing text data

This assignment aimed to help us learn the process of performing sentiment analysis, classification, or topic modeling using text analysis methods as demonstrated in class and in the readings. See detailed instructions for this homework assignment [here](https://cfss.uchicago.edu/homework/text-analysis/). The data (text) used for this assignment were from the `gutenbergr` package.

## Required packages

The following packages were used:

```r
library(tidyverse)
library(gutenbergr)
library(tidytext)
library(wordcloud)
```

## Files included

The following files were included in this repository:

* [lesmiz.Rmd](lesmiz.Rmd) - sentiment analysis of Les Misérables text
* [lesmiz.md](lesmiz.md) - the output of sentiment analysis
* [lesmiz_files](lesmiz_files) - the graphs generated in the Rmd file
* [deh.Rmd](deh.Rmd) - my (failed) attempt at downloading the lyrics of Dear Evan Hansen; this has nothing to do with my homework analysis, but I decided to include it anyways because I spent so much time on it