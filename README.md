# An Analysis of Taylor Swift ‘Through the Eras’

Hello everyone! Welcome to the main page of the repository for our STAT 365 final project, An Analysis of Taylor Swift ‘Through the Eras’. This work explores how the danceability of Taylor Swift's albums, as quantified by their danceability scores, is associated with their critical reception as reflected in Metacritic ratings and audience scores. For our first analysis, we investigate whether there is a significant association between audience ratings and danceability scores of Swift’s music. We follow a similar approach for analysis two, instead looking at whether there is a substantial association between critic ratings and danceability scores of Swift’s music. 

Please take a look through the following files:

`data`:

`taylor_albums_joined`: The merged, analytical data set our group worked with for subsequent analyses. We explored two data sets with each observation representing a Taylor Swift song. The first dataset explores the site Metacritic, which acts as a compiler of reviews from across the internet and print media. They do not issue their reviews and just create a composite Metacritic score for films, television, and music. On their site, they also host blogs in which Metacritic users can review media as well. This Metacritic dataset is simply the Metacritic and user scores for Swift’s albums. The other dataset for this study encompasses Taylor Swift's entire discography to date, from her debut album release in 2006 through to her most recent work as of 2022, excluding singles released separately from an album (e.g., "Only the Young," "Christmas Tree Farm") and non-Taylor-owned albums that have a Taylor-owned alternative (e.g. “Fearless (Taylor’s Version)” is included in this dataset instead of “Fearless”, which is owned by Swift’s previous record label, Big Machine Records). W. Jake Thompson conducted the data collection process on October 17, 2023. sourcing information, including lyrical and audio features, for each Taylor Swift song from a Spotify Web API by obtaining an access token to request artist data for musical attribute scores of the songs. Spotify's API technology for analyzing musical attributes served as the primary specialized equipment used in the data collection. This tool allows for the extraction of information about song characteristics, including tempo, key, mode, and more, based on digital signal processing algorithms (Spotify for Developers). Data collection was entirely digital and relied on advanced computational methods, eliminating the need for traditional physical equipment. Additional information, such as album release dates, track names, and user/Metacritic scores were compiled from authoritative music industry databases and chart records (e.g. Genius.com, Metacritic.com).

`data_raw` in `data`:

Contains the raw, unedited files `taylor_album_songs.csv` and `taylor_albums.csv` that we scraped from W. Jake Thompson's [Tidy Tuesday entry on October 17th, 2023](https://github.com/rfordatascience/tidytuesday/tree/master/data/2023/2023-10-17). 

`documents`:

Contains written documents associated with this project including our data proposal (`stat365group7datadesc+contract.pdf`), original research questions (`original_rqs`), mini projects (`MP_2`), and rough draft (`stat365roughdraft.pdf`).

`results`:

Contains file of R code and output for simple linear regression analysis, including residual diagnostics (see `results.html` for a more readable file and `figure-html` in `results_files` to see individual figures)

`scripts`:

Similar to results folder. Includes all R code used for reading in data, merging data, simple linear regression analyses, and creating figures for our results section (see `Main_project_file.html` for a more readable file).



