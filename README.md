# spotify-to-aws-project

ETL Pipeline: Spotify API > AWS [CloudWatch trigger > Lambda (Python) > S3 > Crawler > Glue > Athena]

### Architecture Diagram

![Architecture Diagram](https://media.licdn.com/dms/image/D4E22AQElmJVBRVcLVQ/feedshare-shrink_1280/0/1699018039964?e=1717027200&v=beta&t=tuUnJa6i-A0aS41z6puuqIw7pncKZx77dLDAU1SMq3E)

### Services Used

1.  [**Spotify API**](https://developer.spotify.com/documentation/web-api) - Used API to pull album, artist, and song data from the top 50 songs on Spotify in the US
2.  **AWS Lambda**
3.  **AWS CloudWatch**
4.  **AWS Glue Crawler**
5.  **AWS Glue Data Catalog**
6.  **AWS Athena**
