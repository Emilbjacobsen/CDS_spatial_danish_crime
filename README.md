# CDS_spatial_danish_crime
This the repo for our CDS_spatial final project product



## Running the scripts
This repo has 3 RMD scripts, one for data wrangling, one for our Shiny integrated Tmap and 1 for spatial auto correlation.


Here is a list of the script for the project and the order in which they are meant to be run:

1. rmd_date_prep.Rmd (data wrangling)
2. rmd_shiny_app.Rmd (map)
3. rmd_get_moran.Rmd (spatial auto correlation)
4. graphs.Rmd (graphs)


## Data
The data can be obtained from Danmarks statistik. if you want to download your own data, keep in mind that no csv files are premade and you wil have design them yourself on the website.
Link: https://www.statistikbanken.dk/statbank5a/default.asp?w=1352


The data we used can be obtained from this github repo under the data folder.

## Using the app
When run the code should launch a window that will initially be empty. There are 4 categories available and when clicked they show the map. There is also a slider so the user can see the year to year transition of crime-rates.
