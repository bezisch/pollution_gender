Replication code for a book chapter on industrial toxicity and female labor market outcomes in the US (2022). 

The repository contains two R Markdown files.

dataset_creation_pollution_gender.Rmd prepares the underlying datasets: processing EPA RSEI tract-level pollution scores and retrieving ACS 5-year census variables (earnings, hours worked, etc.) at census-tract level. Python prepares the RSEI toxicity file, R picks it up and merges it with the ACS variables.

analysis_pollution_gender.Rmd produces all maps and outputs shown in the chapter, including bi-variate choropleth maps of female inactivity, employment, and earnings against toxicity exposure, regional overlays for Rust Belt, South, and Utah highlighting proximity to battery and solar manufacturing facilities, co-location statistics, and a ranked county-level export.
