# p8105_hw1_db3180
---
title: "p8105_hw1_db3180"
author: "Divya Bisht"
date: "9/18/2018"
output: github_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
library(tidyverse)
```
# Problem 1
Creating a data frame:
```{r}
  set.seed(1)
  
  problem1_df = tibble(
  runif(rnorm(10), min = 0, max = 5),
  
  a_logical = c(TRUE, TRUE, TRUE, TRUE, TRUE, TRUE, TRUE, TRUE, TRUE, TRUE),
  b_char = c("My", "attempt", "for", "Problem", "one", "but", "not", "sure", "if", "correct"),
  c_factor = factor(c("blue", "green", "blue", "green", "blue", "green", "blue", "green", "blue", "green"))
 
  )
```


