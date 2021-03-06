# Generation of R Analysis Reports using RMarkdown

| Audience | Computational Skills | Prerequisites | Duration |
:----------|:----------|:----------|:----------|
| Anyone | Beginner/Intermediate R | Working knowledge of R/RStudio | 3 hour workshop|

### Description

This repository has teaching materials for a **3 hour**, hands-on **Generation of R Analysis Reports using RMarkdown** workshop led at a relaxed pace. 

Reproducible research is as important for computational analysis as it is at the bench. Integrating your R data analyses into a report format allows for easy retrieval of the packages/versions and code used to generate your results and figures. It allows for efficient communication of your results with your collaborators. The **knitr** R package allows for the easy generation of professional reports for any R analysis, while allowing for customization and easy revision. In this 3-hour workshop, we will cover the simple RMarkdown syntax and explore options for customizing your reports.

### Learning Objectives
*  **Understand Rmarkdown syntax and available features:** Exploring the syntax of the Rmarkdown language and different available features.
*  **Utilize `knitr` for report generation:** Practicing with `knitr` and different `knitr` options for customizing reports.

> These materials are developed for a trainer-led workshop, but also amenable to self-guided learning.


### Contents

| Estimated Duration           |  Lesson  |  Instructor |
|:------------------------:|:------------------------------------------------:|:--------:|
| 13:00 - 13:10 | [Workshop Introduction](https://github.com/hbctraining/Rmarkdown_analysis_reports/raw/main/lectures/Intro_to_workshop.pdf) | Mary |
| 13:10 - 13:30 | [Introduction to Reproducibility](https://github.com/hbctraining/Rmarkdown_analysis_reports/blob/main/lectures/reproducibility-tools.pdf) | Meeta |
| 13:30 - 14:15 | [RMarkdown Basics](https://hbctraining.github.io/reproducibility-tools/lessons/01-Rmarkdown_basics.html) | Mary |
| 14:15 - 14:20 | Break | |
| 14:20 - 15:05 | [RMarkdown Intermediate](https://hbctraining.github.io/reproducibility-tools/lessons/02-Rmarkdown_intermediate.html) | Meeta | 
| 15:05 - 15:50 | [Practice with RMarkdown](lessons/Rmarkdown_practice.md) | Mary | 
| 15:50 - 16:00 | [Wrap-up](https://github.com/hbctraining/Rmarkdown_analysis_reports/raw/main/lectures/Workshop_wrapup.pdf) | Mary | 


### Setup and Installation Requirements

Download the most recent versions of R and RStudio for your laptop:

 - [R](http://lib.stat.cmu.edu/R/CRAN/) 
 - [RStudio](https://www.rstudio.com/products/rstudio/download/#download)

Install the below packages on your laptop from CRAN. You DO NOT have to go to the CRAN webpage; you can install as follows:


```r
install.packages("tidyverse")
install.packages("pheatmap")
```

Load the libraries to ensure the packages properly installed:

```r
library("tidyverse")
library("pheatmap")
```

## Answer keys
* [**RMarkdown practice answer key**](https://raw.githubusercontent.com/hbctraining/reproducibility-tools/master/activities/Rmd_exercise4_answerkey.rmd)


## Resources

### R Markdown
-   [knitr in a knutshell](http://kbroman.org/knitr_knutshell/)
-   [knitr book](https://www.amazon.com/gp/product/1498716962)
-   [knitr examples](https://yihui.name/knitr/demos)
-   [knitr vignettes](https://github.com/yihui/knitr/tree/master/vignettes)
-   **knitrBootstrap** package for [example reports](https://github.com/jimhester/knitrBootstrap#examples) and for [adding themes](https://github.com/jimhester/knitrBootstrap#bootstrap-themes)
-   The [DT package](https://rstudio.github.io/DT/) - for fancy tables in Rmarkdown


### Reproducibility guidelines
* [HMS R3 Effort](https://ari.hms.harvard.edu/research-rigor-reproducibility/hms-r3-effort)

***

*These materials have been developed by members of the teaching team at the [Harvard Chan Bioinformatics Core (HBC)](http://bioinformatics.sph.harvard.edu/). These are open access materials distributed under the terms of the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0), which permits unrestricted use, distribution, and reproduction in any medium, provided the original author and source are credited.*
