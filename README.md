# Applied Predictive Modeling - R code examples

This is a collection of exercises adapted from [Applied Predictive Modeling](https://www.springer.com/statistics/life+sciences,+medicine+%26+health/book/978-1-4614-6848-6) by Max Kuhn and Kjell Johnson.

I work through various exercises, but apply some alterations to the original code. Here, I try to use some newer R packages to more easily work with data. This was done so that I can better learn modeling, Rmarkdown and git/github.

---
## Working with data using applied modeling
* **Data Pre-processing**
  * *Transformations*
  * *Filtering*
  * *Creating Dummy Variables*
  * *Exercises*
* **Over-Fitting and Model Tuning**
  * *Data Splitting*
  * *Resampling*
  * *Basic Model Building in* **R**
  * *Determination of Tuning Parameters*
  * *Between-Model Comparisons*
  * *Exercises*
  
---
## Tips for new modelers in **R**
The [CRAN](http://cran.r-project.org/index.html) website offers a useful package `ctv`, ([CRAN Task Views](http://cran.r-project.org/web/views/)), that groups various related packages together. For example, the task view for "Machine Learning" would install a set of predictive modeling packages:
```r
# First install the task view package
install.packages("ctv")
# Load the library and install "Machine Learning" task view
library(ctv)
install.views("MachineLearning")
```
Views can be kept up-to-date with `update.views("MachineLearning")`.


