
---
title: "R for data science: tidyverse and beyond"
knit: "bookdown::render_book"
author: "Maxine"
date: "2019-12-16"
site: bookdown::bookdown_site
documentclass: book
new_session: yes
github-repo: enixam/rfordatascience
---


# 前言 {#preface .unnumbered}  

内容主要基于 [R for Data Science](https://r4ds.had.co.nz/index.html) 和 [Advanced R](https://adv-r.hadley.nz/) 两本书，第一部分原书中的内容翻译借鉴了中文译本。目前基本再现了原书中对 tidyverse 核心包的实践.计划在第一部分后探索学习更多的数据科学 R 包，随缘更新。  

绝大部分代码示例需要首先加载 tidyverse, 其中包含的 R 包默认已经被加载好 : 


```r
library(tidyverse)
```
