# Machine Learning Module

## Overview

Machine learning is a widely used tool for predicting environmental data. This module builds on previously used datasets to teach and practice broad concepts in machine learning. It uses the tidymodels framework to break down machine learning into a repeatable set of step. While the tidymodel approach which is specific to R, the goal is for students to understand the process of machine learning that transcends the particular package or programming language environment.

-   author: Quinn Thomas (@rqthomas)
-   contact: [rqthomas\@vt.edu](mailto:rqthomas@vt.edu){.email}
-   date: 2023-03-17
-   license: MIT, CC-BY
-   copyright: Quinn Thomas

## Feedback

<https://github.com/frec3044/machine-learning/issues>

## Questions

-   What is the ice-off day of year in the future for a lake
-   How much carbon is stored in vegetation across the U.S.

## Ojectives

-   Apply machine learning using the tidymodels package to multiple datasets
-   Use machine learning and tidymodels to predict how much carbon is stored in vegetation across the U.S.

## Requires

Experience with the tidyverse data input and wrangling

Completion of two other modules on GitHub

-   [Lake ice phenology](https://github.com/frec3044/lake-ice)
-   [Vegetation carbon](https://github.com/frec3044/land-carbon)

## Instructions

-   Read and execute `assignment/machine-learning-101.qmd` in Rstudio
-   Complete the notebook `assignment/assignment-part-1.qmd` in RStudio
-   `render` + commit output files to GitHub
-   Read and execute `assignment/example-with-tuning.qmd` in Rstudio
-   Complete the notebook `assignment/assignment-part-2.qmd` in RStudio
    -   `render` + commit output files to GitHub

## Context

This module has been developed as the second module in a junior-level Environmental Data Science course at Virginia Tech. The course is require for majors in the Environmental Data Science degree. The course has a pre-requisite course that introduces students to tidyverse concepts. It assumes that students have set of Git and GitHub and understand how to commit and push through Rstudio.

## Timeframe

2-weeks (4 75-minute class periods are allocated to this module)

## Background Reading

Tidymodels has an excellent ["Get Started Page"](https://www.tidymodels.org/start/). It includes the following tutorials.

-   [Build a model](https://www.tidymodels.org/start/models/)
-   [Preprocess your data with recipes](https://www.tidymodels.org/start/recipes/)
-   [Evaluate your model with resampling](https://www.tidymodels.org/start/resampling/)
-   [Tune model parameters](https://www.tidymodels.org/start/tuning/)

## References

The tidymodels framework and package is described the online book:

Kuhn, M and J. Silge. 2022. *Tidy Modeling with R.* O'Reilly Press. <https://www.tmwr.org>
