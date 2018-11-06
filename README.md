# Trailers Analysis

Analysis of trailer usage and experiment on trailer recommendations

# Data import Notes

actions table breaks with .csv import.

    mysql -h 127.0.0.1 -u web -p ML3_mirror -e "select userId, loginId, movieId, youtubeTrailerId, positionInList, action, tstamp from log_trailer_actions" > log_trailer_actions_nojson.tsv

# Data Preparation

    In order to run the analysis, please first run the code in the 'Dataframe Preparation.ipynb' notebook. This notebook reads from raw data and generate dataset necessary for other analysis.
