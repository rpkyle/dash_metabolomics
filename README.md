# Dash Metabolomics

![](dash_metabolomics.gif)

![](dash_metabolomics_1.png)


This is a repo to demonstrate how to build a Dash app in R for metabolomics data. It is under development and therefore not yet deployed on a server. This app in particular makes use of common packages for metabolomics analysis including `metaboAnalystR`, `heatmaply`.

## Running an app
You will need to run applications from the root directory of the repository. e.g., if the name of the app you want to run is `my_dash_app` and the app filename is
`app.R`, you would need to run RScript `apps/my_dash_app/app.R` from the root of the repository. Alternatively you can run an app from within RStudio using Source. However, this will not include the styling. For more info on developing Dash apps in R: https://dashr.plotly.com/

The assets folder contains the CSS styling of the app and header. 

