# Music Streaming Application Data ETL Pipeline using Python and AWS
## Overview
Developed an ETL pipeline using Python and AWS services to obtain the artist, album, and song information from the “Top 100 tracks” playlist on Spotify. This playlist is updated every week. The pipeline involves extracting data from the Spotify API using the spotipy python library, transforming the data to prepare it for analysis, loading the transformed data into Amazon S3, and querying the transformed data using Amazon Athena, utilizing AWS Glue for cataloging.
