# spotify-hit-analysis

🎵 Spotify Hit Rate Analysis

Do followers predict a hit song?

📌 Project Overview

This project analyzes ~8,800 music tracks to evaluate whether an artist’s number of followers predicts the success of individual songs. The analysis combines Python (exploration & statistics) with Power BI (business storytelling) to move from descriptive to diagnostic insights.

🎯 Business Question

Does having more followers increase the probability of releasing a hit song?

🛠️ Tech Stack

Python (Pandas) – Data exploration, feature engineering, correlation analysis

Power BI – Data modeling, DAX measures, and interactive dashboards

GitHub – Project versioning and documentation

🔄 Data Preparation (Python)

Filtered and selected key variables:

track_popularity

artist_followers

artist_popularity

artist_genres

Created a binary feature:

is_hit → track popularity ≥ 80

Performed correlation analysis:

Followers vs track popularity → r ≈ 0.23 (weak relationship)

📊 Key Metrics (DAX)

Total Tracks

Hit Rate (%) – reusable KPI built using CALCULATE and DIVIDE

🔍 Key Insights

Low Predictive Power of Followers:
The correlation between artist followers and track popularity is weak, indicating that a large audience does not guarantee a hit.

Creative Efficiency by Genre:
Genres such as Funk Rock, Rock, and Hip Hop show higher hit rates, even without the largest average follower bases.

Viral Dynamics:
The scatter analysis reveals multiple hit songs produced by artists with relatively small audiences, suggesting viral mechanisms independent of follower count.

📈 Dashboard Preview
KPIs

Hit Rate by Genre

Followers vs Track Popularity

🧠 Conclusion

Having more followers does not guarantee a hit song.
Success at the track level is influenced by genre dynamics and viral exposure rather than audience size alone.
