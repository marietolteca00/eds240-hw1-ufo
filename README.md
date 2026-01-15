---
output:
  pdf_document: default
  html_document: default
---
# Homework #1 (Interpreting `{ggplot2}` code)
### UFO Sightings by Locations

### Author: Marie Tolteca, Student, Master in Environmental Data Science
### Date: 1/14/2026

This repository contains the `HW1.qmd` template file, necessary for completing HW #1. Here, I will be interpreting, explaining, and reflecting on code written by someone else. Find the full assignment description on the [course website](https://eds-240-data-viz.github.io/course-materials/assignments/HW1.html).

The importance of this repository is to be able to identify and decode the code written by someone else. As well as note different ways to create visualization, such as unconventional layouts and  transparency to display counts to display story telling in a different way. This covers data wrangling, text preparations (quotes), using ggplot or element text, and compiling all graphs into one page. The final output is an infographic saved as a png, saved in the folder 'outputs'.

Data Access:
The National UFO Reporting Center is what we will be using for `ufo sighting csv`. This dataset was retrieved from TidyTuesday. Link: `https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2023/2023-06-20/ufo_sightings.csv`

The data from `places` is a population dataset that comes from `sunrise-sunset.org` by `Jon Harmon`. Link: `https://sunrise-sunset.org/`

Packages Used:
```
library(colorspace)
library(geofacet) 
library(ggtext) 
library(glue) 
library(grid)
library(magick)
library(patchwork) 
library(scales) 
library(showtext) 
library(tidyverse) 
library(ggplot2)
```

