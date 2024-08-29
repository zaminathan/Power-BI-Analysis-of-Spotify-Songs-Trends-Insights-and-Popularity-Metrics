# Power-BI-Analysis-of-Spotify-Songs-Trends-Insights-and-Popularity-Metrics
This project involves analyzing Spotify song data using Power BI to uncover trends, insights, and metrics related to song popularity, genres, and artist performance.
To effectively showcase your Power BI analysis of Spotify songs as a project, you should include the following key elements:

### Objective
The objective of this project is to explore the Spotify song dataset to identify trends in song popularity, analyze genre distributions, and understand the attributes that contribute to a song's success.

### Data Source
The dataset was sourced from Spotify's API and includes attributes such as song title, artist, genre, popularity score, release date, and various song characteristics.

### Tools and Technologies Used
This analysis was conducted using Power BI for data visualization and Python for data extraction and cleaning.

### Data Preparation and Cleaning
Data was cleaned by removing duplicates, handling missing values, and normalizing text fields. Additional calculated columns, such as `Year` and `Genre_Category`, were created for more detailed analysis.

### Key Visualizations and Dashboards
- Overview Dashboard: Shows key metrics like total number of songs, average popularity, top genres, and top artists.
- Song Attributes Dashboard: Visualizes relationships between song attributes like danceability, energy, tempo, and valence using scatter plots and histograms.
- Time Series Dashboard: Displays trends in song popularity and genre popularity over time with line and area charts.

### Insights and Analysis
The analysis revealed that pop and hiphop are the most popular genres on Spotify, with a noticeable increase in danceable tracks over the past decade. Additionally, songs with higher energy levels tend to have higher popularity scores.
1. Most Streamed Track:
Track: "Blinding Lights" by The Weeknd
Streams: 370,389,0574
Release Date: November 29, 2019
Musical Attributes:
Energy: 80%
Liveness: 9%
Speechiness: 7%
Danceability: 50%
Instrumentalness: 0% (implied by lack of data)

2. Trending Tracks:
Top 5 trending tracks are displayed with album covers, including "Blinding Lights" by The Weekend, "Shape of You" by Ed Sheeran, "Someone You Loved" by Lewis Capaldi, "Dance Monkey" by Tones and I, and "Sunflower" by Post Malone.

3.Streams by Release Date:
A significant increase in streams is observed around 2020, indicating a surge in Spotify's user engagement or a release of highly popular tracks during this period.

4.Monthly Streaming Patterns:
Highest Average Streams: September with 734.64M streams.
Consistent High Streaming Months: August and October, each showing strong streaming numbers, with August having 631.27M streams.
Total Tracks: 952 tracks analyzed over the time period.

5. Daily Streaming Patterns:
Peak Streaming Day: Friday, with 0.24T streams, indicating a tendency for users to engage more with music towards the weekend.
Lowest Streaming Day: Sunday, with 0.03T streams, which may suggest a decline in listening habits as the weekend ends



### Challenges and Solutions
One challenge was dealing with missing data for some song attributes. This was addressed by using mean imputation for numerical fields and mode imputation for categorical fields.

### Conclusion
This analysis provides valuable insights into the factors that contribute to a song's success on Spotify, which can be leveraged by artists and producers to optimize their content for maximum reach and engagement.

### Future Work
Future work could include incorporating listener demographic data to understand audience preferences better and expanding the dataset to include more recent songs for a current trend analysis.



