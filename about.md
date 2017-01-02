---
layout: page
title: About SGP
---

### An R Package for the calculation & visualization of student growth percentiles and percentile growth trajectories/projections

The **SGP** Package (Betebenner, VanIwaarden, Domingue, Shang, 2015) is an open source package built for the open source **R** software environment (R Development Core Team, 2015). 
The classes, functions and data within the **SGP** package are used to calculate student growth percentiles and percentile growth trajectories/projections using large scale, longitudinal assessment data. The methodology uses quantile regression to estimate the conditional density associated associated with each student's achievement history. Percentile growth projections/trajectories are calculated using the coefficient matrices derived from the quantile regression analyses and specify the percentile growth required for students to reach future achievement targets.

* [sgp.io](https://sgp.io)
* [CRAN Repo](https://cran.R-project.org/package=SGP)
* [GitHub Repo](https://github.com/CenterForAssessment/SGP)

### Team Members

The **SGP** Package is crafted with :heart: by:

* [Damian Betebenner](https://github.com/dbetebenner)
* [Adam VanIwaarden](https://github.com/adamvi)
* [Ben Domingue](https://github.com/ben-domingue)
* [Yi Shang](https://github.com/shangyi)

We love feedback and are happy to answer questions.


### Install the latest stable release from [CRAN](https://cran.r-project.org/package=SGP)

```R
install.packages("SGP")
require(SGP)
```


### Install latest development release from [Github](https://github.com/CenterForAssessment/SGP/) :octocat:

```R
install.packages("devtools")
require(devtools)
install_github("SGP", "CenterForAssessment")
require(SGP)
```

To install from Github you might need: Windows: Rtools (http://cran.r-project.org/bin/windows/Rtools/), OS X: xcode (from the app store),
Linux: apt-get install r-base-dev (or similar).


### To use the SGP Package

The [SGP Package Wiki](https://github.com/CenterForAssessment/SGP/wiki/Home) contains instructions on how to prepare data and run SGP analyses.


### Bibliography

Betebenner, D. W., VanIwaarden, A., Domingue, B., and Shang, Y. (2017). SGP: Student Growth Percentiles & Percentile Growth Trajectories.

R Development Core Team (2017). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria.
3-900051-07-0.
