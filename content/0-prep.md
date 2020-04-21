---
title: Prep
nav: true
--- 

# Workshop Prep

Please ensure that you have the latest version of R **and** R studio before coming for the workshop! Download the most recent versions of R and RStudio for the appropriate OS using the links below:

1. [R](https://cran.r-project.org/)
2. [RStudio](https://rstudio.com/products/rstudio/download/#download)

In the unlikely event that there are problems with installing R and R Studio, you can use RStudio Cloud, but you'll need **a laptop that can access the internet**.  

3. The set of relevant R packages, which you can install by connecting to the internet, opening RStudio, and running:  

    `install.packages(
        c("remotes", "rmarkdown", "skimr", "knitr", "tidyverse", "kableExtra")
    )
    remotes::install_github('yihui/xaringan')`

4. For best experience during the workshop, please have a second monitor or second display to follow along with the demonstration. If you do not have one, it is okay. You can also follow along with your copy of the materials.

If you're a new R user, it's possible that installing R will be challenging. In that case, feel free to ignore the instructions and just count on RStudio Cloud. You can also contact me at [winson.yang@ttu](mailto:winson.yang@ttu.edu) before the workshop so we can troubleshoot together.
