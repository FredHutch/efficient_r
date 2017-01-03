# How to build this presentation

```
# clone this repository
git clone https://github.com/FredHutch/efficient_r.git
cd efficient_r
```

Now start R and within R, do the following:


```{r}
install.packages(c("rmarkdown", "profvis", "ggplot2movies",
"microbenchmark"),repos="https://cloud.r-project.org/")
library("rmarkdown")
render('efficient_R.Rmd')
q('no')
```

This generates the file `efficient_R.html` which you can now
open in a web browser.
