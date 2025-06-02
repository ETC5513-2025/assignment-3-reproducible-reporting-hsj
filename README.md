# ETC5513 Assignment 3

## Group Members

-   Tran Dang Huy (Andy)
    -   Student ID: 32365977
    -   Email: [scha0351\@student.monash.edu](mailto:scha0351@student.monash.edu)
    -   Contributed Branches: `andy`, `andy-slides`, `main`
-   Sia Chawla
    -   Student ID: 35373776
    -   Email: [scha0351\@student.monash.edu](mailto:scha0351@student.monash.edu)
    -   Contributed Branches: `sia-discussion`, `sia-executive-summary` `sia-slides`, `main`
-   Jiaqi Xu (Jackie):
    -   Student ID: 30095158
    -   Email: [jxuu0058\@student.monash.edu](mailto:jxuu0058@student.monash.edu)
    -   Contributed Branches: `rf-model`, `jackie-slides`, `main`

## Group Project Topic

### Education & Career Success

link to the dataset: <https://www.kaggle.com/datasets/adilshamim8/education-and-career-success>

## Renv environment

### What is renv?

renv tool can help to create a reproducible environments where it is easier to share the project in a way that everyone can get the same package version like us.

### How to use renv and what has been installed before hand?

The files that account for renv environment in our project are renv/, renv.lock and .Rprofile

Before starting with renv, make sure you have renv package, if not then you can install it using `install.packages("renv")`

You can start renv environment installed before hand in the project by `renv::restore()`, by doing this you will load the library that have been installed in the project inside renv.lock so you don't need to download the libraries again, it also make sure your version for the package is the same version when we create this project.

To deactivate the renv environment use `renv::deactivate()` to do it

For more informations about other things you could do with renv, please have a look at: <https://rstudio.github.io/renv/articles/renv.html>
