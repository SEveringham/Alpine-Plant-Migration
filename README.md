# Alpine-Plant-Migration
Code for analyses of Australian alpine plant migration 

There are 4 Rmarkdown files, that were coded in the following order:

1) "Get Google Elevation Data.Rmd" - is the Rmd used to get all the accurate elevation data from the historic atlas of living Australia records from their latitude and longitude

2) "Cleaning ALA data to Final Data.Rmd" - is the code that takes the ALA data and merges it with modern data and then cleans everything. It is also where we filter for species to be used for the other analyses (hypothesis 2 and 3)

3) "Linear models and graphin final data.Rmd" - is the linear models (Elevation ~ Year) for each species individually. And then graphing these linear relationships for each species with their upper and lower quantiles (this makes figures 1 & 2 in the manuscript for this analysis)

4) "Quantile regression.Rmd" - is the analysis for the upper (95%) and lower (5%) quantiles for each species individually.

5) "Meta-analyses for all species.Rmd" - is the overall meta-analyses across species for their mean regression trends, their upper quantile trends and their lower quantile trends. It also plots the forest plots for this information found in the supplementary material for this manuscript.
