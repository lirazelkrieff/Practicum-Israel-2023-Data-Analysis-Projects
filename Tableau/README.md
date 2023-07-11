# Trending Youtube videos analysis

You work as a video ad analyst at the Sterling & Draper advertising agency. You devote a lot of time to analyzing trending videos on YouTube to determine what content deserves marketing attention.
Each video has a specific category (Entertainment, Music, News & Politics, etc.), region, and trending date.

Dashboard data content:
- Trending videos from the past, broken down by day and category
- Trending videos, broken down by countries
- A table of correspondence between categories and countries

Parameters according to which the data is to be grouped:
- Trending date and time
- Video category
- Country

The data:
- Trending history — absolute values with a breakdown by day (two graphs: absolute numbers and percentage ratio)
- Events, broken down by countries — relative values (% of events)
- The correspondence between the categories and countries — absolute values (a table)


Data sources for the dashboard: an aggregate table called trending_by_time.
- record_id — primary key
- region — country/geographical region
- trending_date — date and time
- category_title — the video category
- videos_count — the number of videos in the trending section

Link to Tableau Dashboard: https://public.tableau.com/views/TrendingVideosAnalysisbyCountryandCategory-Practicum/Dashboard1
