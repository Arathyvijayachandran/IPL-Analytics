# IPL-Cricket Insights 

## Overview
The Cricket Analytics Suite is a comprehensive data analysis project designed to extract actionable insights from cricket match data. Leveraging advanced data science techniques, this suite provides in-depth player performance metrics, venue-based analytics, match outcome predictions, and more. The project is ideal for cricket enthusiasts, analysts, and data scientists looking to explore trends, visualize patterns, and build predictive models for T20 or ODI cricket matches.

## Features
The project is organized into several key modules, each addressing a unique aspect of cricket analytics:

1. Player Performance Analysis
Techniques: GroupBy, Aggregations, Visualizations, K-Means Clustering
Identify top batters by total runs, strike rate, and boundary percentage.
Rank top bowlers by wickets, economy rate, dot ball percentage, and strike rate.
Create all-rounder rankings using combined batting and bowling metrics.
Visualize batting average vs. strike rate using scatter plots and cluster batters/bowlers into archetypes (e.g., power hitters, anchors, death bowlers).
2. Venue & City Insights
Techniques: GroupBy, Geospatial Heatmaps
Analyze best/worst stadiums for batting or bowling based on historical data.
Calculate city-wise average first innings scores.
Study toss impact per venue and playing conditions.
Generate geospatial heatmaps to visualize match outcomes by location.
3. Toss & Match Outcome Impact
Techniques: Chi-Square Test, Decision Trees
Investigate the correlation between toss-winning and match-winning probabilities.
Analyze toss decision trends (bat vs. field) across seasons and venues.
Build decision trees to identify key features (e.g., toss, city, team) that predict match winners.
4. Run Rate & Overwise Momentum
Techniques: Time Series, Line Plots, Rolling Averages
Study over-wise scoring patterns in Powerplay, Middle, and Death overs.
Analyze momentum by calculating run rate evolution over overs.
Compare run rate trends for chasing vs. defending teams.
5. Match Result Prediction (ML Model)
Techniques: Classification (Random Forest, XGBoost)
Predict match winners using features like toss winner, toss decision, venue, target runs, and powerplay score.
Split data into training/testing sets and evaluate model accuracy.
6. Team vs Team Head-to-Head Stats
Techniques: GroupBy, Pivot Tables
Provide historical win-loss records between any two teams.
Calculate average scores when batting first or second.
Visualize head-to-head stats using stacked bar or radial charts.
7. Super Over & Nail-Biter Matches
Techniques: Filtering, Storytelling
Filter close matches (margin < 5 runs or 1 wicket).
Identify players who excel under pressure.
Highlight matches involving Super Overs or Duckworth-Lewis-Stern (DLS) method.
8. Season-Level Trends
Techniques: Time Series, Line Charts
Track the evolution of average match scores across seasons.
Analyze the impact of rule changes (e.g., new ball, Powerplay rules).
Study seasonal performance trends for teams and players.
