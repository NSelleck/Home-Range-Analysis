# Home Range Analysis

Home Range Analysis Exercise for BIOL 5700, Advanced Data Analytics<br></br>

This assignment involved creating Minimum Convex Ploygons and Kernel Density Estimates using data from my previous thesis project. <br></br>

Assignment Webpage - https://nselleck.github.io/Home-Range-Analysis/ <br></br>

# References for home range analysis in R:
Below you will find resources and tutorials with will provide assistance with this exercise.

## Dataset was collected at Cheatham Wildlife Management Area. The ID's for each bird was changed for ease of use with the line of code for splitting the csv. In the original data set, LOWA 1, LOWA 2, and LOWA 3 were called "barry_b", "xmas", and "trashcan" respectively. 

## Packages
- adehabitat: https://cran.r-project.org/web/packages/adehabitatHR/adehabitatHR.pdf
- move: https://cran.r-project.org/web/packages/move/vignettes/move.pdf
- moveVis: https://cran.r-project.org/web/packages/moveVis/moveVis.pdf 
- plotly: https://cran.r-project.org/web/packages/plotly/plotly.pdf
- pbapply: https://cran.r-project.org/web/packages/pbapply/pbapply.pdf 
-don't forget maptools.

## Tutorials
- Home Range Analysis: https://cran.r-project.org/web/packages/adehabitatHR/vignettes/adehabitatHR.pdf
- Movement Visualization: http://movevis.org/ and http://movevis.org/articles/example-3.html
- Date and Time Conversions: https://www.rdocumentation.org/packages/base/versions/3.6.1/topics/as.POSIX*

## Helpful site for selecting color schemes
- http://colorbrewer2.org

## For PC users with Java Complications
- just download Java
```
library('ggmap')

stamen <- get_stamenmap(bbox = c(left = -87.4, bottom = 36.5, right = -87.3, top = 36.6),
          zoom = 14, maptype = "terrain")

ggmap(stamen)
```