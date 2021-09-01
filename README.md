# Alpine-Plant-Migration
Code for analyses of Australian alpine plant migration 

There are 7 Rmarkdown files, that were coded in the following order:

1) "Get Google Elevation Data.Rmd" - is the Rmd used to get all the accurate elevation data from the historic atlas of living Australia records from their latitude and longitude

2) "Cleaning ALA data to Final Data.Rmd" - is the code that takes the ALA data and merges it with modern data and then cleans everything. It is also where we filter for species to be used for the other analyses (hypothesis 2 and 3)

3) "Linear models and graphin final data.Rmd" - is the linear models (Elevation ~ Year) for each species individually. And then graphing these linear relationships for each species with their upper and lower quantiles (this makes figures 1 & 2 in the manuscript for this analysis)

4) "Quantile regression.Rmd" - is the analysis for the upper (95%) and lower (5%) quantiles for each species individually.

5) "Meta-analyses for all species.Rmd" - is the overall meta-analyses across species for their mean regression trends, their upper quantile trends and their lower quantile trends. It also plots the forest plots for this information found in the supplementary material for this manuscript.

6) "NSW Alpine Climate Analysis.Rmd" - is an analysis and graphing of temperature and snow depth in the alpine region

7) "Reanalysis of species with outlier data before 1985.Rmd" - is a file to reanalyse 8 species' mean elevation, upper quantile elevation and lower quantile elevation regressions after removing outlier data. Data before 1985 was removed from these species as they only had three data points before 1985 and no data between 1985-2000. This was a suggested extra analysis and now post-hoc test that arose during a peer review process.
