# IPL-Data-Analysis-Dashboard
Interactive IPL Analytics Dashboard built using Power BI to visualize team performance, match outcomes, and season-wise trends using real-world IPL datasets.

🚀 Project Overview

This project is an interactive data visualization dashboard built using Microsoft Power BI Desktop to analyze Indian Premier League (IPL) data.

The dashboard provides insights into:

Team performance
Match results across seasons
Player achievements (e.g., Player of the Match)
Trends and comparisons across IPL seasons

It is designed to help users explore IPL data visually and make data-driven observations.

📁 Project Structure

├── shashiuu.pbix                # Main Power BI report file

├── teams_data.csv               # Dataset containing IPL teams info

├── ipl_matches_data.csv         # Dataset containing match-level data

└── README.md                   # Project documentation


📂 Dataset Description

1. teams_data.csv

Contains information about IPL teams:

team_id → Unique ID for each team

team_name → Name of the team

short_name → Abbreviation (e.g., MI, RCB)

image_url → Team logo


2. ipl_matches_data.csv

Contains match-level details:

match_id → Unique match identifier

season_id → IPL season

team1, team2 → Competing teams

winner → Match winner

player_of_match → Best player

venue, city → Match location

result → Win/other outcomes


📊 Features of the Dashboard

🏏 Team Performance Analysis

      - Total matches played
      
      - Wins by each team
      
📅 Season-wise Insights

      - Performance trends across IPL seasons
      
🌍 Venue Analysis

      - Matches played across different cities/stadiums
      
⭐ Player Highlights

      - Player of the Match statistics
      
📈 Interactive Visualizations

      - Filters (slicers) for season, team, etc.
      
      - Dynamic charts and graphs
      
🛠️ Tools & Technologies Used

      - Power BI Desktop → Data visualization & dashboard creation
      
      - CSV Files → Data source
      
      - DAX (Data Analysis Expressions) → Calculations & measures
      
      
▶️ How to Run the Project

Step 1: Install Power BI

Download and install:
👉 https://powerbi.microsoft.com/

Step 2: Open the Project
1. Open Power BI Desktop
2. Click File → Open

Select: shashiuu.pbix

Step 3: Load Data (if needed)
If the dataset is not loaded:

Go to Transform Data / Data Source Settings

Reconnect:

    - teams_data.csv
    - ipl_matches_data.csv

Step 4: Explore Dashboard

    Use filters/slicers to:
    
        - Select seasons
        
        - Compare teams
        
        - Analyze performance
        

💡 Use Cases

    📊 Data analytics practice project
    🎓 Academic submission / mini project
    💼 Portfolio project for data analyst roles
    🏏 Sports analytics exploration

🔮 Future Enhancements

    - Add player-level statistics (runs, wickets)
    - Integrate real-time IPL data APIs
    - Add predictive analytics (win probability)
    - Convert to Power BI Service for web sharing
