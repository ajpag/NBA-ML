# NBA Clustering on Skillsets
_Joe Marlo, Andrew Pagtakhan, George Perrett, Bilal Waheed_

The project is an unsupervised approach to discover underlying patterns or groupings between NBA compensation vs.
overall team skillsets. It uses K-means, hierarchical, and model-based clustering along with other techniques and tools such as principal component analysis, standardizing, scaling, and web-scraping.

To run the analyses, first ensure `seasons_stats_clean.csv` is within`/Data`. If it isn't, run `Data/Clean_all_data.R` which cleans the original data and outputs the `.csv`.

`/Analyses` contains the clustering analyses  
`/Data` contains the cleaned data, cleaning scripts, and scraping scripts  
`/Inputs` contains the raw data. Original data can be found on [kaggle.com](https://www.kaggle.com/drgilermo/nba-players-stats)
