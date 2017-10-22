# A short course on nonparametric curve estimation

[![Travis-CI Build Status](https://travis-ci.org/egarpor/SSS2-UC3M.svg?branch=master)](https://travis-ci.org/egarpor/nonpar-eafit)
[![License](https://img.shields.io/badge/license-CC_BY--NC--SA_4.0-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

![KDE animation](https://github.com/egarpor/nonpar-eafit/blob/master/images/images/kde.gif)

## Overview

A module within the subject *Robust and nonparametric statistical techniques* for the course 2017/2018 of the [MSc in Applied Mathematics](http://www.eafit.edu.co/programas-academicos/posgrado/maestria-matematicas-aplicadas/Paginas/inicio.aspx) at [EAFIT University](http://www.eafit.edu.co/) (Colombia).

## Syllabus

The notes are available at <https://bookdown.org/egarpor/nonpar-eafit>.

Here is a broad view of the syllabus:

1. [Introduction](https://bookdown.org/egarpor/nonpar-eafit)

  1. [Course objectives and logistics](https://bookdown.org/egarpor/nonpar-eafit/intro-course.html)
  2. [Background and notation](https://bookdown.org/egarpor/nonpar-eafit/intro-background.html)
  3. [Nonparametric inference](https://bookdown.org/egarpor/nonpar-eafit/intro-nonpar.html)
  4. [Main references and credits](https://bookdown.org/egarpor/nonpar-eafit/intro-credits.html)

2. [Density estimation](https://bookdown.org/egarpor/nonpar-eafit/dens.html)

  1. [Histograms](https://bookdown.org/egarpor/nonpar-eafit/dens-hist.html)
  2. [Kernel density estimation](https://bookdown.org/egarpor/nonpar-eafit/dens-kde.html)
  3. [Asymptotic properties](https://bookdown.org/egarpor/nonpar-eafit/dens-kdeasymp.html)
  4. [Bandwidth selection](https://bookdown.org/egarpor/nonpar-eafit/dens-bwd.html)
  5. [Confidence intervals](https://bookdown.org/egarpor/nonpar-eafit/dens-ci.html)
  6. [Practical issues](https://bookdown.org/egarpor/nonpar-eafit/dens-prac.html)
  7. [Exercises](https://bookdown.org/egarpor/nonpar-eafit/dens-exercises.html)

3. [Regression estimation](https://bookdown.org/egarpor/nonpar-eafit/reg.html)

  1. [Review on parametric regression](https://bookdown.org/egarpor/nonpar-eafit/reg-param.html)
  2. [Kernel regression estimation](https://bookdown.org/egarpor/nonpar-eafit/reg-kre.html)
  3. [Asymptotic properties](https://bookdown.org/egarpor/nonpar-eafit/reg-asymp.html)
  4. [Bandwidth selection](https://bookdown.org/egarpor/nonpar-eafit/reg-bwd.html)
  5. [Local likelihood](https://bookdown.org/egarpor/nonpar-eafit/reg-loclik.html)
  6. [Exercises](https://bookdown.org/egarpor/nonpar-eafit/reg-exercises.html)

4. Appendix A: [Installation of `R` and `RStudio`](https://bookdown.org/egarpor/nonpar-eafit/installation-of-r-and-rstudio.html)
5. Appendix B: [Introduction to `RStudio`](https://bookdown.org/egarpor/nonpar-eafit/introduction-to-rstudio.html)
6. Appendix C: [Introduction to `R`](https://bookdown.org/egarpor/nonpar-eafit/introduction-to-r.html)

## List of animations

**Important:** the links below point towards `https` urls with auto-signed SSL certificates. That means that you most likely will get a **warning from your browser** saying that "Your connection is not private". Click in "Advanced" and allow an exception. `https` has been considered since it allows to include the apps in both `http` and `https` websites.

* Nonparametric density estimation
	* [Bias and variance of the moving histogram](https://bookdown.org/egarpor/nonpar-eafit/dens-hist.html#dens-movhist)
	* [Construction of the kernel density estimator](https://bookdown.org/egarpor/nonpar-eafit/dens-kde.html)
	* [Bandwidth selection in kernel density estimation](https://bookdown.org/egarpor/nonpar-eafit/dens-bwd.html#dens-comp)
	* [Transformation of kernel density estimator](https://bookdown.org/egarpor/nonpar-eafit/dens-prac.html#dens-transf)
* Nonparametric regression estimation
	* [Construction of the local polynomial regression estimator](https://bookdown.org/egarpor/nonpar-eafit/reg-kre.html)
	* [Construction of the local likelihood estimator](https://bookdown.org/egarpor/nonpar-eafit/reg-loclik.html)
* Multiple linear regression
  * [Least squares and distance choice](https://bookdown.org/egarpor/nonpar-eafit/reg-param.html#reg-lin)
* Logistic regression
  * [Logistic curve and maximum likelihood fit](https://bookdown.org/egarpor/nonpar-eafit/reg-param.html#reg-log)
* Other
	* [An illustration of nonparametric vs parametric estimation](https://bookdown.org/egarpor/nonpar-eafit/intro-nonpar.html)

## Contributions

Contributions, reporting of typos, and feedback on the notes are very welcome. Either send an email to <edgarcia@est-econ.uc3m.es> or (preferably) fork the repository, make your changes and open a pull request. Give me a reason for listing your name below!

## License

All material in this repository is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
