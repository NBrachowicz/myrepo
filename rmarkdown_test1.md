---
title: "R Markdown test1"
author: "Atoj"
date: "18/10/2019"
output: 
  html_document: 
    keep_md: yes
editor_options: 
  chunk_output_type: inline
---

```{r}
## insert your brilliant WORKING code here

library(tidyverse)
diamonds
diamonds %>% ggplot() +
  geom_point(aes(carat, price), alpha = 0.01)

```

