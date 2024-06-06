# spotify-to-aws-project

ETL Pipeline: Spotify API > AWS [CloudWatch trigger > Lambda (Python) > S3 > Crawler > Glue > Athena]

### Architecture Diagram

![Architecture Diagram](https://raw.githubusercontent.com/rokusho235/spotify-to-aws-project/main/awsPipeline.png)

### Services Used

1.  [**Spotify API**](https://developer.spotify.com/documentation/web-api) - Used API to pull album, artist, and song data from the top 50 songs on Spotify in the US
2.  **AWS: Lambda, CloudWatch, Glue Crawler & Data Catalog, Athena**
