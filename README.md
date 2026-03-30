# ANALYSIS_OF_IPL_2025_BATTERS

## Project Overview

This repository presents a data-driven analysis of batting performances in the IPL 2025 season using a structured dataset of 200 players across 10 franchises. The project applies exploratory data analysis and visualization techniques to evaluate individual and team-level batting efficiency, scoring patterns, and milestone achievements.

## Dataset Description

The dataset `ANALYSIS_OF_IPL_2025_BATTERS.csv` contains one row per player with the following key features:

- Team name  
- Total runs scored  
- Matches played, innings batted, and not-outs  
- Highest individual score and batting average  
- Balls faced and strike rate  
- Centuries (100s) and fifties (50s)  
- Number of fours and sixes  

The data covers all 10 IPL 2025 franchises and supports comparison of batting strength, consistency, and aggression across teams.

## Analysis Workflow

The Jupyter notebook `ANALYSIS_OF_IPL_2025_BATTERS.ipynb` includes the end-to-end analysis pipeline: 

- Loading and preparing the IPL 2025 batters dataset  
- Computing team-wise aggregates (total runs, average runs per player, average strike rate, milestones, matches played)  
- Generating visualizations to study batting performance at player and team level  
- Interpreting trends in scoring patterns, boundary-hitting, and batting depth  

A concise report in `ANALYSIS_OF_IPL_2025_BATTERS.pdf` documents the methodology, plots, and key insights. 

## Visualizations

Key visual components of the analysis are:

- **Top run-scorer per team**  
  - Bar chart highlighting the leading run-scorer for each franchise and their total runs, indicating teams that relied heavily on a single batter.  

- **Balls faced vs runs scored**  
  - Scatter plot with a regression line showing a positive relationship between balls faced and runs, and revealing variation in scoring efficiency among players.  

- **Team-wise run distribution**  
  - Box plot of player runs by team, comparing medians, spread, and outliers to illustrate batting depth and consistency across franchises.  

## Key Insights

Selected findings from the analysis include:

- PBKS recorded the highest total runs (3000) and the highest average strike rate (144.91), indicating the strongest overall batting unit.  
- GT and LSG displayed strong and consistent batting performances, while KKR registered the lowest total runs (1886).  
- Sai Sudharsan emerged as the tournament’s standout batter with 759 runs.  
- There is a clear positive correlation between balls faced and runs scored, while variations in strike rate reflect different batting strategies.  
- RCB registered the most fifties (22), and SRH scored the most centuries (3), highlighting distinct scoring strengths across teams.  

## Repository Structure

- `ANALYSIS_OF_IPL_2025_BATTERS.csv` – IPL 2025 batting dataset for 200 players.
- `ANALYSIS_OF_IPL_2025_BATTERS.ipynb` – Jupyter notebook containing the full analysis and visualizations.
- `ANALYSIS_OF_IPL_2025_BATTERS.pdf` – PDF report summarizing results and interpretations. 
- `LICENSE` – MIT License for this project.

## Getting Started

1. Clone the repository:  
   ```bash
   git clone https://github.com/arvind14322/ANALYSIS_OF_IPL_2025_BATTERS.git
   ```
2. Open `ANALYSIS_OF_IPL_2025_BATTERS.ipynb` in Jupyter Notebook, JupyterLab
