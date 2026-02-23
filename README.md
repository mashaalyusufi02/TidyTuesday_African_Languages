## Acknowledgements

This R project was developed from data provided from the TidyTuesday repository. Tidy Tuesday was begun by the R for Data Science community to enable individuals to download social data about a particular social subject, explore, visualise, and extend it. *The Languages of Africa* is the dataset used by me in this project, expanded upon, and linked here: [The Languages of Africa](https://github.com/rfordatascience/tidytuesday/blob/main/data/2026/2026-01-13/readme.md)

**Citation** Data Science Learning Community (2024). *Tidy Tuesday: A weekly social data project.* https://tidytues.day

## Reproduce Results

You can reproduce the results by downloading the following [R markdown script](https://github.com/mashaalyusufi02/TidyTuesday_African_Languages/tree/main/R%20Markdown%20script) on this repository. Use R Studio, VS Code, or Positron to open this script.

Copy and paste the code chunk given below onto the first line of the downloaded file and run it.

``` r
install.packages(c("tidyr","stringr","dplyr","purrr","rvest","readr","geofacet","ggtext","extrafont","skimr","spData","terra","sf","ggplot2","tmap","leaflet"))
```

Save the file and note its name.

Give your file name as an argument to `rmarkdown::render()` and run this command in the console.

## Guide to Repository

R Markdown script/ Contains the file necessary to reproduce the main analysis

Plots/ contains all the main figures
