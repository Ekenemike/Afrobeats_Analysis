# Afrobeats_Analysis
I analyzed Afrobeats music performance across Spotify, Apple Music, and YouTube Music using SQL, Google Sheets, and Looker Studio.
## Project Overview

This project analyzes the performance of Afrobeats songs across Spotify, Apple Music, and YouTube Music using SQL, Google Sheets, and Looker Studio. The analysis provides insights into:

✅ Most Streamed Songs & Artists

✅ Revenue Calculation for Spotify & YouTube

✅ Top Growing Songs on YouTube

✅ Most Charted Songs Across Platforms

✅ Comparison of Artist Rankings on Different Platforms

📍 Final Deliverable: A Looker Studio Dashboard presenting key insights from the analysis.

## Dataset Sources used

- <a href=https://github.com/Ekenemike/Afrobeats_Analysis/blob/main/open.csv>Dataset1</a>

- <a href=https://github.com/Ekenemike/Afrobeats_Analysis/blob/main/charts.csv>Dataset2</a>

- <a href=https://github.com/Ekenemike/Afrobeats_Analysis/blob/main/youtube-charts-top-songs-ng-weekly-20250206.csv>Dataset3</a>

##  Live music charts for updated rankings:

- <a href=https://open.spotify.com/playlist/37i9dQZEVXbLw80jjcctV1>Spotify</a>

- <a href=https://music.apple.com/bh/playlist/top-100-nigeria/pl.2fc68f6d68004ae993dadfe99de83877>Apple Music</a>

- <a href=https://charts.youtube.com/charts/TopSongs/ng/weekly>YouTube Music</a>

## Tools & Technologies Used

✔ SQL (BigQuery) → Data Cleaning & Querying

✔ Google Sheets → Dataset Organization

✔ Looker Studio → Interactive Reports & Visualizations

✔ Python → (Optional for further analysis)

✔ Instant Data Scraper → Web scraping tool for extracting real-time data from streaming platforms

## Data Collection Process

To gather streaming data, we used Instant Data Scraper, a browser extension that automates data extraction from web pages. The steps followed:

1️⃣ Navigate to the Official Charts: Open the respective pages for Spotify, Apple Music, and YouTube charts.

2️⃣ Configure Instant Data Scraper: Set up scraping parameters to extract relevant song, artist, and ranking data.

3️⃣ Export Data to CSV: Save extracted data for further processing in SQL and Google Sheets.

4️⃣ Load into Google Sheets: Clean and organize data before running SQL queries in BigQuery.

This method ensured I had real-time, structured data for analysis without manual data entry errors.

## Dasboard Reports

- <a href=https://lookerstudio.google.com/s/r7mqqUCZF-4>Report 1</a>

- <a href=https://lookerstudio.google.com/s/uXpCXG_V-P0>Report 2</a>

- <a href=https://lookerstudio.google.com/s/pDkMjgWr4fc>Report 3</a>

- <a href=https://lookerstudio.google.com/s/uPHWxeG1qCQ>Report 4</a>

- <a href=https://lookerstudio.google.com/s/jYweYoBX0kc>Report 5</a>

- <a href=https://lookerstudio.google.com/s/g6QMkLUzs6g>Report 6</a>

## Data Visualization in Looker Studio

🎯 Interactive Dashboard Includes:

✅ Top 10 Most Streamed Songs 

✅ Total Revenue Breakdown 

✅ Most Frequent Artists 

✅ Song Performance Across Platforms 

✅ Fastest-Growing Songs on YouTube

## Key Business Recommendations
1️⃣ Leverage YouTube for Music Discovery

Viral growth on YouTube does not guarantee Spotify/Apple Music traction (e.g., Tems’ "Love Me Jeje").
Music marketers should focus on converting YouTube traction into Spotify & Apple streams.

2️⃣ Prioritize Spotify for Revenue

Spotify pays significantly more per stream than YouTube.
Artists should push listeners toward Spotify to maximize earnings. (e.g., ODUMODUBLVCK and Rema) both dominate the Spotify Charts in terms of earnings from streams.

3️⃣ Cross-Promotion is Crucial

Artists with high cross-platform presence (e.g., Wizkid, Asake, Burna Boy) dominate the charts.
Labels should distribute releases evenly across streaming platforms.

4️⃣ Long-Lasting Songs Drive Brand Retention

Omah Lay's "Understand" spent 63 weeks on the charts, proving longevity matters for branding.
Sustained marketing strategies can help keep songs charting longer.

## Challenges Faced

1️⃣ Data Merging Issues: Initially attempted to merge all query results into a single Google Sheets file, but this led to misalignment issues where different query results appeared under the wrong columns.

2️⃣ Finding a Better Approach: Instead of merging, I decided to keep each query result as a separate sheet and use Looker Studio to build individual reports for each insight.

3️⃣ Query Optimization: Some SQL queries required refining to handle NULL values and ensure accurate revenue calculations.

4️⃣ Looker Studio Setup: Setting up correct visualization types for different metrics and ensuring interactive filters worked properly.

5️⃣ Scraping Limitations: Using Instant Data Scraper required continuous monitoring to ensure extracted data was structured correctly and did not miss essential details.

How to Use This Repository

1️⃣ Clone the repository:

git clone https://github.com/Ekenemike/Afrobeats_Analysis.git

2️⃣ Open the SQL Queries folder for all SQL scripts.

3️⃣ Open the Data folder for original datasets used.

4️⃣ Open the Looker Studio Report to explore the dashboard.

👨‍💻 About Me

🎵 Passionate about data-driven insights in the music industry, the business world and geopolitical Analysis

💡 Always exploring SQL, Data Analytics, and Music Business Trends.

📢 Contact & Contributions

📌 Found an issue or want to collaborate? Feel free to open a pull request!

📧 Email: Ekenemike@outlookl.com🔗 

LinkedIn: http://www.linkedin.com/in/ekene-m-ahuche

🚀 If you find this project useful, please ⭐ star the repo!




