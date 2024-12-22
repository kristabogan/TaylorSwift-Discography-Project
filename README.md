# Taylor Swift Song Analysis Project

In August, I decided to tackle a personal data project to answer a question I had been asked many times: *"What's your favorite Taylor Swift song?"* I realized I couldn’t pick just one, so I decided to dive deeper into her entire discography and analyze her songs using data!

## Project Overview

Over the course of a few weeks, I rated each of Taylor Swift's songs on 7 key metrics:
- **Emotional Impact**
- **Enjoyability**
- **Lyricism**
- **Messaging**
- **Nostalgia**
- **Overall Sound**
- **Overall Weighted Score** (derived from the above metrics)

I used a detailed spreadsheet from [u/melanorrigby on r/TaylorSwift](https://www.reddit.com/r/TaylorSwift/) (shoutout for the excellent framework!) to organize my rankings and ensure consistency.

### Statistical Analysis

To wrap up my analysis, I ran an **ANOVA** to determine if there were any significant differences in my rankings across Taylor Swift's albums. The goal was to see if I favored any particular album significantly more than others.

### Interactive Dashboard

Instead of just showing the results through static visuals, I created an [interactive Tableau dashboard](https://public.tableau.com/app/profile/krista.bogan/viz/TaylorSwiftRankingsDashboard/Dashboard1) that allows users to explore the data and insights in real-time. The dashboard includes:
- A song ranking comparison across the 7 metrics
- A detailed breakdown of my favorite albums and songs
- A view of how each album compares to others in terms of my rankings

### Results

- **Top Albums**: *folklore* and *evermore* emerged as my favorite albums, with significant differences in my rankings compared to other works in her discography.
- **Top Song**: My all-time favorite Taylor Swift song? *"illicit affairs"* from *folklore*, which earned a perfect score of 10!

This project was a fun and insightful way to combine my love for Taylor Swift with my data skills, providing valuable hands-on experience in Python statistical analysis and Tableau visualization.

## Files Included

- `tsrankings.csv`: The dataset with my rankings of each Taylor Swift song across the 7 metrics.
- `TaylorSwiftSideProject.ipynb`: The Python Jupyter notebook with the analysis, including the ANOVA test.
- `visualizations/`: Folder containing the Tableau visualizations and dashboard file.

Feel free to explore the code and analysis, and let me know if you have any questions!
