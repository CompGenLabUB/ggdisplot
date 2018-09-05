# ggdisplot

Very simple scatterplot with two density plots. I use it often, so here it is.

```r
# INSTALLATION
library(devtools)
install_github("scastlara/ggdisplot")

# USAGE
library(ggdisplot)
ggdisplot(iris, "Sepal.Length", "Sepal.Width", "Species")
```

<img width="400px" src="ggdisplot.png">
