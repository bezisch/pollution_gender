Preparation_Pollution_RSEI_2022_Tract.ipynb prepares tract-level toxicity data from the EPA's Risk-Screening Environmental Indicators (RSEI) database for 2022. 

It loads RSEI geographic microdata for census tracts, merges it with 2022 Census Gazetteer files to add land area and geographic identifiers, constructs state and county FIPS codes from the 11-digit tract GeoID, and computes per-capita and per-square-mile exposure measures. 

The notebook also adds county names via external FIPS lookup, produces exploratory visualizations (log-scale strip plots, KDE distributions, correlation heatmaps across toxicity measures), and identifies the highest-exposure tracts nationally. 

The main output variables are ToxConc, CancToxConc, NonCancToxConc, and the composite RSEI Score, all at the census tract level.
