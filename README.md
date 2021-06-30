# Biobank-Dashboard
This repository is for storing codes related to Biobank analysis and dashboard.

This repository consist of:

* clean.R - It is a file for merging and cleaning the data and exporting the dataset.csv.
* dataset.csv - The cleaned file is complete and ready to use.
* Dashboards.Rmd - The file that the dashboard is generated from. flexdashboard framework and runtime with shiny.
* app.R - Shiny web app file

### Usage
start to run clean.R 
you will get dataset.csv

=> If you want to open a dashboard created from flexdashboard + shiny, 
you need to open file Dashboards.R  by clicking `run document`
Or click on file and then click on `Knit Document`.

=> If you want to open a dashboard created from shiny only,
You need to open the app.R file by clicking `run app`.

### shinyapp.IO 

I tried deploying Dashboards.R file, you can check it out at...https://thanrada.shinyapps.io/Dashboards/?_ga=2.39631520.229271646.1625041166-1597395094.1623831708
Note: The website takes a long time to load.
