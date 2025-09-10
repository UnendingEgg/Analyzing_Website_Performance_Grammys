# Analyzing_Website_Performance_Grammys

## Description
Analysis of Grammy's website performance before and after being split into two, using pandas and plotly express to create visualizations of data.

This project investigates web traffic patterns for the Grammys and Recording Academy websites, particularly around the split of the sites in February 2022. Using time-series analysis and visualization, I explored how the website split effected user engagement, and recommended next steps based on said analysis.

## Key Findings
1. Engagement on both websites spikes sharply during award night, with smaller peaks at nominee announcements.
2. Engagement remains relatively flat outside of key events, suggesting strong event-driven traffic.
3. Following the website split, the split sites had higher engagement (more pages per session, lower bounce rate) alone than the combined site.

## Tools & Libraries
Python 3.9+ - Data manipulation
Pandas - Data cleaning & manipulation
Plotly Express - Visualizations

## Datasets

grammy_live_web_analytics.csv and ra_live_web_analytics.csv both contain data analytics about the Grammys website and Recording Academy website respectively. Columns include:

1. date, the date data was gathered
2. visitors, visitors to the website
3. pageviews, total views of different pages the website got that day
4. sessions, how many sessions the webpage got that day
5. bounced_sessions, how many sessions resulted in no user interaction
6. avg_session_duration_secs, the average duration of a session in seconds
7. awards_week, whether or not the day was during award week
8. awards_night, whether or not the day was during award night

grammys_age_demographics.csv and tra_age_demographics.csv both contain age demographic data about the Grammys website and Recording Academy website respectively. Columns include:

1. age_group, the age buckets that users could fall into
2. pct_visitors, the percentage that an age bucket made of the total site traffic

## How to Run

1. Clone this repository.
2. Install dependencies:
```
pip install pandas plotly jupyter
```
3. Open jupyter notebook
```
jupyter notebook 
```
4. In the browser window that opens, navigate to M6_NYC_Schools.ipynb and open it.
