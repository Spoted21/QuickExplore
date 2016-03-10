# QuickExplore
Quickly explore smaller datastes with a Shiny app. This can be run easily from github:

```r
library(shiny)

runGitHub("QuickExplore", "Spoted21")
```

##### If you encounter an error while runnning try installing the dependencies before running the app.
```r
if(!require("downloader")) install.packages("downloader", dependencies=TRUE)

if(!require("httr")) install.packages("httr", dependencies=TRUE)

if(!require("shiny")) install.packages("shiny", dependencies=TRUE)
```
