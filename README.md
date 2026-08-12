# IPL Analysis Dashboard (2008–2025)

![IPL Dashboard](Images/IPL_Dashboard.png)

## Overview

This project is an interactive **IPL Analysis Dashboard** developed using **Microsoft Power BI**. It analyzes Indian Premier League data from **2008 to 2025** and provides insights into team performance, player achievements, match statistics, venues, and season-wise results.

The dashboard allows users to select an IPL season and dynamically explore important statistics.

## Dashboard Preview

The dashboard includes:

- Season Winner
- Season Runner-up
- Total Matches
- Total Teams
- Total Sixes
- Total Fours
- Number of Venues
- Orange Cap statistics
- Purple Cap statistics
- Team Points Table
- Matches Won and Lost
- Season-wise analysis

## Key Features

### Season Analysis
Select an IPL season to view:

- Season winner
- Runner-up
- Total matches
- Participating teams
- Number of venues
- Total boundaries

### Orange Cap Analysis

Displays the leading batsman for the selected season, including:

- Orange Cap holder
- Team
- Total runs

### Purple Cap Analysis

Displays the leading wicket-taker for the selected season, including:

- Purple Cap holder
- Team
- Total wickets

### Points Table

The dashboard provides a dynamic points table containing:

- Team name
- Matches played
- Matches won
- Matches lost
- No Result
- Total points

## Tools & Technologies

- **Microsoft Power BI**
- **DAX**
- **Power Query**
- **Data Modeling**
- **Data Visualization**
- **CSV Dataset**

## Dataset

The project uses IPL match-level and ball-by-ball data.

Main datasets:

- `ipl_matches_data.csv`
- `ball_by_ball_data.csv`

The data is transformed and modeled in Power BI to create relationships between matches, teams, players, and ball-by-ball information.

## DAX Concepts Used

Some of the major DAX concepts used in this project include:

- `CALCULATE()`
- `FILTER()`
- `SELECTEDVALUE()`
- `SUM()`
- `COUNTROWS()`
- `DISTINCTCOUNT()`
- `MAXX()`
- `MINX()`
- `RELATED()`
- `ALL()`
- `TOPN()`
- Variables using `VAR` and `RETURN`
- Conditional logic using `IF()`

## Data Modeling

The Power BI data model connects match-level data with ball-by-ball data and supporting team/player information.

This enables the dashboard to calculate season-specific statistics dynamically based on the selected IPL season.

## Key Insights

The dashboard can be used to analyze:

- Which team won a particular IPL season
- Which team finished as runner-up
- Highest run scorer of a season
- Highest wicket-taker of a season
- Team wins and losses
- Total points earned by teams
- Number of matches played
- Total sixes and fours
- Number of venues used during a season
- Overall team performance

## Project Structure

```text
IPL-Analysis-PowerBI/
│
├── README.md
│
├── Dashboard/
│   └── IPL_Analysis.pbix
│
├── Dataset/
│   ├── ipl_matches_data.csv
│   └── ball_by_ball_data.csv
│
├── Images/
│   └── IPL_Dashboard.png
│
└── Documentation/
    └── Project_Documentation.pdf
```

## How to Use

1. Download or clone this repository.
2. Open the `.pbix` file using Microsoft Power BI Desktop.
3. Make sure the dataset paths are correctly configured.
4. Refresh the data if required.
5. Select an IPL season from the season slicer.
6. Explore the dashboard and interact with the visualizations.

## Project Objective

The objective of this project is to demonstrate how **Power BI, DAX, data modeling, and data visualization** can be used to transform IPL cricket data into an interactive analytical dashboard.

## Skills Demonstrated

- Data Analysis
- Data Cleaning
- Data Transformation
- Data Modeling
- DAX
- Power BI
- KPI Development
- Interactive Dashboard Design
- Sports Analytics
- Business Intelligence

## Dashboard

The dashboard provides an interactive view of IPL performance from **2008–2025**, allowing users to explore different seasons and compare team and player performance.

## Author

**Shoheb Mulla**

Data Analyst | Power BI | Python | SQL | Data Visualization

---

⭐ If you find this project useful, consider giving the repository a star.