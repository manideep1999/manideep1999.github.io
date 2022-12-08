---
date: '4'
title: 'World Map - Candidate Status'
cover: './WorldMap.png'
#github: 'https://github.com/bchiang7/spotify-profile'
#external: 'https://ieeexplore.ieee.org/document/9008088'
tech:
  - Java
  - SQL
  - HTML
---

Based on the statistics of the candidates scheduled, attended, ongoing, and completed tests, a dynamic live dashboard showing the candidates' numbers for each country was shown. The live data of the test takers in a certain country is shown as the mouse is over that nation. From the db batch and candidate tables, a one to many mapping is done to fetch the data of the number of the candidate status in a specific batch every minute using a cron job.

<!-- Displaying a dynamic live dashboard of the candidates count on a world map for every country based on the statistic of the candidates Scheduled, Attended, Test In Progress & Test Completed. As the mouse hovers over a specific country, the live data taking the exam in that country is displayed. The data is fetched regularly for the data base tables which gets updated for every 2 min cron job.  -->
