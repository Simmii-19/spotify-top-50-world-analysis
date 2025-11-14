# Spotify Top 50 World – Power BI Analysis

This project is an analysis of the Spotify Top 50 World dataset using Power BI.  
I created this to explore global music trends, understand which artists appear most often, and see how things like popularity, release dates, duration, and explicit content affect chart performance.

Since the PBIX file is too large for GitHub, I’ve uploaded it to Google Drive.  
You can download it here:

PBIX Download:  
https://drive.google.com/file/d/1ZEoC4fV_N4VWXl7HUdeLSKDhbc4aaXFA/view?usp=sharing

The repository includes the dataset, a PDF version of the dashboard, and all the DAX measures used in the report.

---

## What’s Included
spotify-top-50-world-analysis
│
├── spotify-top-50-world.csv # Dataset
├── Spotify.pdf # Dashboard preview
├── DAX-Measures.txt # All DAX formulas
└── README.md # Documentation
---

## Project Summary

I used this dataset to answer some questions such as:

- Which artists show up the most in the Top 50?
- What does popularity look like across all songs?
- Are explicit songs more common?
- Do singles perform differently from album tracks?
- How do older songs perform compared to newer ones?
- Is there any relationship between a song’s popularity and its chart position?

The visuals in Power BI helped break down these patterns in a simple, interactive way.

---

## Dataset Details

The dataset contains information like:

- Song name  
- Artist  
- Chart position  
- Popularity score  
- Duration  
- Album type (single or album)  
- Number of tracks  
- Release date  
- Whether the song is explicit  
- Album cover URL  

This allowed for a lot of different types of analysis.

---

## DAX Measures

All DAX measures used in the project are available in:

They include metrics like:

- Total songs  
- Distinct artists and songs  
- Average popularity  
- Best and worst chart positions  
- Average duration  
- Explicit vs non-explicit percentages  
- Release year calculations  
- Song age  
- Popularity vs position correlation  

---

## Simple DAX Dictionary (What the Measures Mean)

Here are quick explanations in normal language:

- **Total Songs** – How many entries are in the dataset  
- **Distinct Artists** – How many different artists appear  
- **Distinct Songs** – Unique songs in the data  
- **Average Popularity** – Average popularity score  
- **Best/Worst Position** – Highest and lowest chart ranks  
- **Explicit Song Count** – Number of explicit songs  
- **Explicit Song %** – Percentage of explicit tracks  
- **Average Total Tracks** – Average number of songs on the albums  
- **Earliest/Latest Release Year** – Oldest and newest songs  
- **Average Song Age** – How old songs are on average  
- **Popularity–Position Correlation** – Shows whether popular songs rank higher  

---

## How to Use This Repository

1. Download or clone the repo:
   ```bash
   git clone https://github.com/<Simmii-19>/spotify-top-50-world-analysis.git
2.View Spotify.pdf to explore the dashboard.

3.If you want to rebuild the dashboard, use the CSV file and DAX measures.

Tools Used

Power BI Desktop

DAX

CSV dataset

GitHub

PDF export

Why I Made This

I wanted to create a clean and interesting Power BI project that analyzes something fun and globally relevant.
This was a great way to practice data modeling, visual design, and DAX skills while digging into music trends.

