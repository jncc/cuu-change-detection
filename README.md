
[<img src="logos.png">](https://jncc.gov.uk/our-work/copernicus-project/)

<p> 

# 'cuu-change-detection'

This R code was developed by JNCC under the Copernicus User Uptake Work Package 6 projects focussing on Habitat Change Detection. It calls from functions from the [habitat-condition-monitoring](https://github.com/jncc/habitat-condition-monitoring) package, which contains various functions involved in the preparation, statistical analysis and modelling with Sentinel-1 and Sentinel-2 data.
<p>
Under the habitat change detection project, in collaboration with Historic Environment Scotland, Natural England, Natural Resources Wales and Scottish Natural Heritage, JNCC used Sentinel-1 and -2 analysis-ready data (ARD) to track change over time at a site and highlight changed areas through a web application.

<p> 

## Site documentation

The markdown documentation walkthroughs the process of deriving the zonal statistics for each of the sites, using the Sentinel imagery from the studied time period and a spatial framework of polygons used to study change. 

* <b> CUUCD_EnglishSites.Rmd </b> - Dark Peak; Malvern Hills

* <b> CUUCD_ScottishSites.Rmd </b> - HES site 2; Insh Marshes SSSI, Glenfeshie and HES site 3; Flanders Moss SSSI and HES site 4; Skyreburn Grasslands SSSI, Lagganmullan SSSI and HES site 1

* <b> CUUCD_WelshSites.Rmd </b> - Cors Bodeilio site; Rhos Tonyrefail square site

<p>

## Change analysis

* <b> change_analysis_examples.Rmd </b> - short initial analysis of Insh Marshes statistics and the values used to flag change.

* <b> change_statistics_analysis.Rmd </b> - Interactive document demonstrating the statistics used for flagging change. Creates a local shiny app using the statistics text file generated from the 'zonal_stats' function, also hosted [here](https://btripps23.shinyapps.io/ChangeStatisticsAnalysis/).