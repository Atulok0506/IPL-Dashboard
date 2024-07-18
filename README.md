# IPL Dashboard

  ![IPL](https://www.zoho.com/sites/zweb/images/analytics/rewind-analytics/blogs-2023-img1.jpg)

![Tool](https://img.shields.io/badge/Tool-Power%20BI-blue)
![Framework](https://img.shields.io/badge/Framework-Power%20Query-yellow)

## Overview
The IPL Dashboard is a comprehensive analysis tool for the Indian Premier League (IPL) seasons from 2008 to 2024. Built using Power BI, it enables users to explore various aspects of IPL data, including team and player performances, match statistics, and historical trends. The dashboard provides insights through interactive visualizations and easy navigation.

## About the Project
**IPL Dashboard** is a Power BI-based analytical tool that provides a detailed view of IPL seasons from 2008 to 2024. It includes various pages with interactive elements such as slicers, charts, and tables to help users gain insights into team and player performances, match statistics, and trends over the years.

## Prerequisites

**Prerequisites:**

1. Power BI Desktop: Ensure you have Power BI Desktop installed on your system.
2. Data Source: Prepare your IPL dataset in a compatible format (https://www.kaggle.com/datasets/atulkishore/ipl-season-2008-to-2024).
3. Basic Understanding of Power BI: Familiarity with Power BI for exploring and interacting with the dashboard.

These prerequisites will help you effectively utilize the IPL Dashboard.

## Getting Started

To begin using the IPL Dashboard:
- Clone the repository to your local machine and open the Power BI file (.pbix) in Power BI Desktop.
- Connect your dataset in the 'Transform Data' section if required.
- Explore various pages and interactive elements to gain insights.
- Feel free to contribute by forking the repository and sharing feedback via GitHub issues.

## Dashboard Pages

### Introduction Page
This page provides an overview of the IPL (Indian Premier League) with general information about the league's history, format, and significance.


   ![IPL Introduction](https://github.com/Atulok0506/IPL-Dashboard/blob/main/IPL%20Introduction.png)


- **Navigation Buttons**: Buttons with links to other pages for easy navigation.

### IPL Overview Page
This page offers a summary of the IPL seasons from 2008 to 2024.

- **Qualifying Teams Table**: Shows the four qualifying teams for each season.
- **Summary Cards**:
  - Total Matches Played
  - Total Seasons
  - Total Teams
- **Bar Charts**:
  - Rank of Stadium by Venue Name
  - Rank of Umpires by TV Umpire
- **Line Charts**:
  - Average Runs per Season (with tooltips)
  - Sum of No Balls and Percent Wide Balls by Season
 
   ![IPL Overview](https://github.com/Atulok0506/IPL-Dashboard/blob/main/IPL%20overview.png)



### Team Profile Page
This page provides detailed information about each team.

- **Slicers**: Filters for teams and seasons.
- **Team Performance Table**: Shows team performance metrics (matches played, won, lost, draw, and rank) for selected seasons.
- **Venue Performance Table**: Displays team performance at various venues, including the number of wins and winning percentage.
- **Parametric Charts**: Clustered bar chart for runs, wickets, boundaries, selected over range, and season, dynamically updating based on slicer selections.
- **Bar Graphs**:
  - Top 5 Wicket Takers
  - Top 5 Run Scorers



   ![IPL Team Profile](https://github.com/Atulok0506/IPL-Dashboard/blob/main/Team%20Profile.png)

### Player Profile Page
This page focuses on individual player performance.

- **Player Slicer**: Select a batsman.
- **Bowler Slicer**: Based on the selected batsman, choose a bowler.
- **Player Performance Metrics**: Displays wickets, strike rate, economy, and number of boundaries against the selected bowler.
- **Bar Charts**:
  - Rank of Bowler
  - Rank of Batsman
  - Rank of Boundary Hitters
 
  - 
  - 
   ![IPL PLayer Profile](https://github.com/Atulok0506/IPL-Dashboard/blob/main/player%20profile.png)
